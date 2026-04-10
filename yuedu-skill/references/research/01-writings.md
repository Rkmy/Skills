# Legado书源/订阅源体系研究

## 一、Legado项目概述

**Legado**（阅读）是一款开源的Android阅读App，核心功能是**书源/订阅源解析**。

- **项目地址**：https://github.com/gedoor/legado
- **核心特性**：
  - 支持自定义书源（小说网站解析）
  - 支持自定义订阅源（RSS/文章网站解析）
  - 支持多种解析方式：CSS选择器、XPath、JSONPath、正则表达式、JavaScript
  - 支持本地TXT/EPUB阅读
  - 支持WebDav同步

## 二、书源体系架构

### 2.1 书源JSON结构

```json
{
  "bookSourceUrl": "源URL",
  "bookSourceName": "源名称",
  "bookSourceGroup": "源分组",
  "bookSourceType": 0,
  "bookSourceComment": "注释",
  "loginUrl": "登录地址",
  "ruleSearch": { /* 搜索规则 */ },
  "ruleBookInfo": { /* 详情规则 */ },
  "ruleToc": { /* 目录规则 */ },
  "ruleContent": { /* 正文规则 */ },
  "ruleExplore": { /* 发现规则 */ }
}
```

### 2.2 数据流流程

```
用户搜索 → 搜索规则 → 获取书籍列表 → 详情规则 → 获取书籍信息
                                              ↓
用户阅读 ← 正文规则 ← 获取章节内容 ← 目录规则 ← 获取目录列表
```

### 2.3 解析方式对比

| 解析方式 | 适用场景 | 优点 | 缺点 |
|:---|:---|:---|:---|
| **CSS选择器** | 静态HTML，结构清晰 | 简洁直观 | 复杂层级定位困难 |
| **XPath** | 需要精确定位 | 功能强大，支持复杂查询 | 语法较复杂 |
| **JSONPath** | JSON API接口 | 解析JSON效率高 | 仅适用于JSON数据 |
| **正则表达式** | 文本提取、复杂匹配 | 灵活强大 | 可读性差，易出错 |
| **JavaScript** | 复杂逻辑处理 | 功能最强大 | 性能较低，调试困难 |

## 三、订阅源体系架构

### 3.1 订阅源JSON结构

```json
{
  "sourceUrl": "源URL",
  "sourceName": "源名称",
  "sourceGroup": "源分组",
  "sourceIcon": "图标URL",
  "ruleArticles": "列表规则",
  "ruleTitle": "标题规则",
  "ruleDescription": "描述规则",
  "ruleLink": "链接规则",
  "ruleContent": "内容规则"
}
```

### 3.2 订阅源类型判断

| 字段组合 | 类型 | 说明 |
|:---|:---|:---|
| 无ruleArticles | 标准RSS | 使用内置RSS解析器 |
| ruleArticles + ruleDescription | 列表+描述 | 直接显示描述内容 |
| ruleArticles + 无ruleDescription | 列表+内容 | 需要抓取全文 |

## 四、核心技术原理

### 4.1 JSOUP解析引擎

Legado使用JSOUP作为HTML解析引擎，支持：
- CSS选择器语法
- DOM遍历和操作
- 属性提取

### 4.2 规则执行顺序

1. **URL变量替换** - 替换`{{key}}`、`{{page}}`等变量
2. **发起请求** - GET/POST请求目标URL
3. **编码处理** - 根据charset参数处理编码
4. **规则解析** - 按规则类型调用对应解析器
5. **结果返回** - 返回提取的数据

### 4.3 JavaScript执行环境

- 基于Rhino/Nashorn JavaScript引擎
- 提供`java`对象访问原生方法
- 提供`book`、`chapter`等上下文对象

## 五、设计哲学

1. **灵活性优先**：提供多种解析方式，适配各种网站结构
2. **渐进式配置**：基础功能简单，高级功能可选
3. **社区驱动**：书源由社区共享，持续更新
4. **去中心化**：不依赖特定服务器，用户自主管理书源

## 六、参考来源

- Legado官方文档：https://github.com/gedoor/legado/tree/master/docs
- 喵公子教程：https://mgz0227.github.io/The-tutorial-of-Legado/
- 源仓库社区：https://www.yckceo.com/