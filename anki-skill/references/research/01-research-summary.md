# Anki Skill 调研摘要

## 信息来源统计

| 来源 | 类型 | 内容维度 |
|------|------|----------|
| Anki Manual PDF (273页) | 一手官方文档 | 功能全貌、模板、算法、设置 |
| docs.ankiweb.net | 一手官方文档 | 官方手册 |
| FSRS FAQ (faqs.ankiweb.net) | 一手官方文档 | FSRS算法问答 |
| StudyCardsAI FSRS Guide | 二手解析 | FSRS算法详解 |
| FSRS4Anki GitHub Wiki | 一手文档 | 算法原理 |
| finjapanlife.com 教程 | 二手教程 | 基础用法 |
| nz.assignment1st.org 教程 | 二手教程 | 背单词用法 |
| kancloud.cn 高考教程 | 二手教程 | 学生实用经验 |
| bbs.marginnote.com.cn | 二手经验 | CSS/模板技巧 |
| geekdaxue.co 万字合集 | 二手经验 | 插件/工具链 |

---

## 核心知识框架（提炼自PDF全文 + 网络调研）

### 1. Anki 核心概念体系

**基础构件**（官方手册提炼）：
- **Note（笔记）**：信息的最小存储单位，包含多个字段（Fields）
- **Card（卡片）**：由笔记生成的学习单元，一个笔记可生成多张卡片
- **Note Type（笔记类型）**：定义字段结构和卡片模板
- **Deck（牌组）**：卡片的组织容器，支持子牌组嵌套
- **Collection（收藏集）**：用户所有卡片和设置的总体

**学习状态机**（官方手册）：
- **New**：未学习的新卡片
- **Learning**：正在学习中（在初始学习步骤内）
- **Review**：已进入复习阶段的成熟卡片
- **Relearning**：遗忘后重新学习的卡片

### 2. 算法体系

**SM-2（旧版）**：
- 基于 SuperMemo 的 SM-2 算法
- 核心参数：ease factor（默认2.5），interval
- 问题：Ease Hell（ease factor越来越低）、不个性化

**FSRS（新版，Anki 23.10+ 默认可用）**：
- DSR 模型：D（难度）、S（稳定性 stability）、R（可提取性 retrievability）
- 核心参数：Desired Retention（目标保留率，默认90%）
- 优势：减少15-20%复习量、无Ease Hell、个性化参数
- 开启步骤：牌组选项 → FSRS开关 → 设置保留率 → Optimize
- FSRS Helper插件（759844606）：完整控制面板

**参数优化建议**（官方FAQ）：
- 每月优化一次，或复习数翻倍时优化
- 不同类型内容建议分开预设
- 只用Again/Good两个按钮也可以正常工作

### 3. 制卡技巧体系

**SuperMemo 20条规则核心原则**：
- 最小信息原则：一张卡片只测试一个知识点
- 不要单纯记忆，要理解后再制卡
- 使用完形填空替代死记硬背
- 问题要用个人化语言表述

**实践技巧**（多个教程综合）：
- 问答分离：正面问题，背面答案
- 信息碎片化：拆分复杂知识
- 图文结合：支持图片/音频/视频
- 留白排版：避免信息密度过高

### 4. 模板与样式

**HTML/CSS 模板系统**（官方手册）：
- 前模板（Front Template）
- 后模板（Back Template）  
- 样式（Styling）：CSS
- 字段引用：`{{FieldName}}`
- 完形填空：`{{cloze:Text}}`
- 条件显示：`{{#Field}}...{{/Field}}`、`{{^Field}}...{{/Field}}`
- TTS（文字转语音）：`{{tts en_US:Front}}`
- FrontSide 引用：`{{FrontSide}}`

### 5. 插件生态

**必装插件**（社区评价综合）：
- **FSRS4Anki Helper**（759844606）：FSRS完整管理面板
- **AnkiConnect**（2055492159）：API接口，连接第三方工具
- **Image Occlusion Enhanced**：图片遮挡制卡
- **Review Heatmap**（1771074083）：复习热力图
- **AnkiXquicker**：极速截图/OCR制卡
- **Obsidian_to_Anki**：与Obsidian笔记联动

### 6. 同步与备份

**AnkiWeb 同步**（官方手册）：
- 免费账号，支持多平台同步
- 手动同步：点击同步按钮
- 冲突解决：手动选择以哪一端为准
- 限制：单文件25MB，总媒体无硬性限制

**本地备份**：
- Tools → Create Backup
- 自动备份位置：用户数据文件夹/backups/
- 建议同时使用外部备份工具

### 7. 常见问题分类

**安装问题**：
- Windows：防病毒误报、DLL缺失
- Mac：安全设置阻止
- Linux：系统Qt版本冲突、GTK主题问题

**使用问题**：
- 卡片积压：降低每日新卡片数、开启FSRS优化
- 间隔过长：提高Desired Retention
- Ease Hell（SM-2）：切换FSRS
- 同步冲突：手动选择正确版本

**模板问题**：
- 图片不显示：检查Media文件夹
- 字段不显示：检查字段名大小写
- CSS不生效：检查.card选择器

---

## 调研质量评估

| 维度 | 来源数 | 质量 | 备注 |
|------|--------|------|------|
| 官方文档（PDF） | 1个，273页 | 最高 | 完整官方手册 |
| 算法（FSRS） | 3个 | 高 | 官方FAQ+详解+源码 |
| 制卡技巧 | 4个 | 中高 | 多个实践教程 |
| 插件生态 | 3个 | 中 | 社区推荐 |
| 故障排查 | 2个 | 中 | 手册+经验帖 |
| 高级模板 | 1个 | 高 | 官方手册 |

**总体评估**：核心内容覆盖完整，一手来源比例 >60%。可以构建高质量Skill。
