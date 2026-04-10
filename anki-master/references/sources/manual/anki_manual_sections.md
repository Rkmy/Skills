# Anki Manual - Extracted Sections

Total pages: 273

Total characters: 314632



## BACKGROUND (17 pages found)

3 ===
Background
Active Recall Testing
Use It or Lose It
Spaced Repetition
Why Anki?
Anki is a program which makes remembering things easy. Because it is a
lot more eﬃcient than traditional study methods, you can either greatly
decrease your time spent studying, or greatly increase the amount you
learn.
Anyone who needs to remember things in their daily life can beneﬁt from
Anki. Since it is content-agnostic and supports images, audio, videos and
scientiﬁc markup, the possibilities are endless. For example:
Learning a language
Studying for medical and law exams
Memorizing names and faces of people
Brushing up on geography
Mastering long poems
Even practising guitar chords!
There are two simple concepts behind Anki: active recall testing and
spaced repetition. They are not known to most learners, despite being
well-documented in scientiﬁc literature. Understanding how these
concepts work will make you a more eﬀective learner.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 3/273


---

4 ===
Active Recall Testing
Active recall testing means being asked a question and trying to remember
the answer. This is in contrast to passive study, where we read, watch, or
listen to something without pausing to consider if we know the answer.
Research has shown that active recall testing is far more eﬀective at
building strong memories than passive study. There are two reasons for
this:
The act of recalling something strengthens the memory, increasing the
chances we’ll be able to remember it again.
When we’re unable to answer a question, it tells us we need to return
to the material to review or relearn it.
You have probably encountered active recall testing in your school years
without even realizing it. When good teachers give you a series of
questions to answer after reading an article, or make you take weekly
tests, they are not doing it simply to see if you understood the material or
not. By testing you, they are increasing the chances you will be able to
remember the material in the future.
A good way to integrate active recall testing into your own studies is to
use ﬂashcards. With traditional paper ﬂashcards, you write a question on
one side of a card, and the answer on the other side. By not turning the
card over until you’ve recalled the answer, you can learn things more
eﬀectively than passive observation allows.
Use It or Lose It
Our brains are eﬃcient machines, and they rapidly forget information
that doesn’t seem useful. Chances are that you don’t remember 

---

5 ===
have spent the last two weeks telling people about how great it was,
you’re likely to still remember it in vivid detail.
The brain’s “use it or lose it” policy applies to everything we learn. If you
spend an afternoon memorizing some science terms, and then don’t
think about that material for two weeks, you’ll probably have forgotten
most of it. In fact, studies show we forget about 75% of material learned
within a 48 hour period. This can seem pretty depressing when you need
to learn a lot of information!
However, the solution is simple: review. By reviewing newly-learned
information, we can greatly reduce forgetting.
The only problem is that traditionally, reviewing has not been very
practical. If you are using paper ﬂashcards, it’s easy to ﬂick through all of
them if you only have 30 of them to review, but as the number grows to
300 or 3000, it quickly becomes unmanageable.
Spaced Repetition
The spacing eﬀect was reported in 1885 by a German psychologist called
Hermann Ebbinghaus. He observed that we tend to remember things
more eﬀectively, if we spread reviews out over time, instead of studying
multiple times in one session. Since the 1930s, there have been a number
of proposals for utilizing the spacing eﬀect to improve learning, in what
has come to be called spaced repetition.
One example was in 1972, when a German scientist called Sebastian
Leitner popularized a method of spaced repetition with paper ﬂashcards.
By separating the paper cards into a series of boxes

---


## GETTING_STARTED (13 pages found)

1 ===
Introduction
Mobile Clients
This is the manual for the computer version of Anki. Separate manuals
are available for the mobile clients:
AnkiDroid Manual (Android)
AnkiMobile Manual (iPhone/iPad)
Quickstart
In a hurry? Jump straight to Getting Started.
Getting Help
Looking for help? Please see Getting Help.
Translations
Volunteers have contributed translations of this manual. The translations
may not always be up to date.
Bahasa Indonesia
Deutsch
Español
Français
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 1/273


---

8 ===
Platform Notes
This section explains the way Anki is installed, and the possible problems
you may encounter, depending on your OS:
Windows
macOS
Linux
If you have already installed Anki, you can skip to the Getting Started
section.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 8/273


---

10 ===
Installing & Upgrading Anki on
Windows
Requirements
Installing
Upgrading
Add-on Compatibility
Problems
Requirements
Recent Anki releases require a computer running the 64 bit version of
Windows 10 or 11.
The last Anki release that supported Windows 7 and 8.1 was Anki
2.1.49.
The last Anki release that supported 32 bit Windows was Anki 2.1.35-
alternate.
If you’re on an old machine, you can obtain old releases from the releases
page.
Installing
To install Anki:
1. Download Anki from https://apps.ankiweb.net.
2. Save the installer to your desktop or downloads folder.
3. Double-click on the installer to run it. If you see an error message,
please see the installation issues page.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 10/273


---


## ADDING_NOTES (79 pages found)

41 ===
Getting Started
Installing & Upgrading
Videos
Key Concepts
Cards
Card States
Decks
Notes & Fields
Card Types
Note Types
Collection
Shared Decks
Installing & Upgrading
The Anki ecosystem is made up of Anki, AnkiMobile, AnkiDroid, and
AnkiWeb, all of which are linked from our oﬃcial website.
For instructions on how to install and upgrade Anki for your computer,
please read the links below:
Windows
Mac
Linux
Videos
For a quick way to dive into Anki, have a look at these intro videos. Some
were made with a previous Anki version, but the concepts are the same.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 41/273


---

44 ===
Decks that have been placed inside another deck are often called
“subdecks”, and top-level decks are called “parent decks”.
Anki starts with a deck called “Default”; any cards which have somehow
become separated from other decks will go here. Anki will hide the
default deck if it contains no cards and you have added other decks.
Alternatively, you may rename this deck and use it for other cards.
Decks in the deck list are sorted alphabetically. This can result in a
surprising order if your deck names contain numbers. For example, “My
Deck 10” will come before “My Deck 9”, as 1 comes before 9. If you want
“My deck 9” to appear earlier, you can rename it to “My deck 09”, which
appears before “My deck 10”.
Decks are best used to hold broad categories of cards, rather than
speciﬁc topics such as “food verbs” or “lesson 1”. For more information
about this, please see the using decks appropriately section.
For information on how the order of decks aﬀects the order cards are
studied in, please see the display order section.
Notes & Fields
When making ﬂashcards, it’s often desirable to make more than one card
that relates to the same information. For example, if you’re learning
French, and you learn that the word bonjour means hello, you may wish
to create one card that shows you “bonjour” and asks you to remember
“hello”, and another card that shows you “hello” and asks you to
remember “bonjour”. One card is testing your ability to recognize the
French word, and the other car

---

46 ===
In Anki, this collection of related information is called a note and each
piece of information is contained in a ﬁeld. In this example, the note has
three ﬁelds: “French”, “English”, and “Page”.
To add and edit ﬁelds, click the Fields… button while adding or editing
notes. For more information on ﬁelds, please see the Customizing Fields
section.
Card Types
In order for Anki to create cards based on our notes, we need to give it a
blueprint that says which ﬁelds should be displayed on the front or back
of each card. This blueprint is called a card type. Each type of note can
have one or more card types; when you add a note, Anki will create one
card for each card type.
All card types have two templates, one for the question and one for the
answer. In the previous French example, we wanted the back of our
recognition card to look like this:
To do this, we can set the answer template to:
In card templates, ﬁeld names are wrapped in double curly brackets, like
{{French}} or {{English}}. Anki replaces those with the actual text the
ﬁelds contain. This is called a “Field replacement”. Text not wrapped in
double curly brackets appears the same on each card. For example, we
won’t need to add “Page #” on every note because the template will add it
Q: Bonjour
A: Hello
   Page #12
Q: {{French}}
A: {{English}}<br>
   Page #{{Page}}
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 46/273


---


## CARDS_TEMPLATES (121 pages found)

3 ===
Background
Active Recall Testing
Use It or Lose It
Spaced Repetition
Why Anki?
Anki is a program which makes remembering things easy. Because it is a
lot more eﬃcient than traditional study methods, you can either greatly
decrease your time spent studying, or greatly increase the amount you
learn.
Anyone who needs to remember things in their daily life can beneﬁt from
Anki. Since it is content-agnostic and supports images, audio, videos and
scientiﬁc markup, the possibilities are endless. For example:
Learning a language
Studying for medical and law exams
Memorizing names and faces of people
Brushing up on geography
Mastering long poems
Even practising guitar chords!
There are two simple concepts behind Anki: active recall testing and
spaced repetition. They are not known to most learners, despite being
well-documented in scientiﬁc literature. Understanding how these
concepts work will make you a more eﬀective learner.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 3/273


---

6 ===
however, as it cannot give you an exact date on which you should review
something again, and it does not work very well with material of varying
diﬃculty.
The biggest developments in the last 30 years have come from the
authors of SuperMemo, a commercial ﬂashcard program that implements
spaced repetition. SuperMemo pioneered the concept of a system that
keeps track of the ideal time to review material and optimizes itself based
on the performance of the user.
In SuperMemo’s spaced repetition system, every time you answer a
question, you tell the program how well you were able to remember it —
whether you forgot completely, made a small mistake, remembered with
trouble, remembered easily, etc. The program uses this feedback to
decide the optimal time to show you the question again. Because a
memory gets stronger each time you successfully recall it, the time
between reviews gets longer and longer — so you may see a question for
the ﬁrst time today, then 3 days later, 15 days later, 45 days later, and so
on.
This was a revolution in learning, as it meant material could be learned
and retained with the absolute minimum amount of eﬀort necessary.
SuperMemo’s slogan sums it up: with spaced repetition, you can: “forget
about forgetting”.
Why Anki?
While there is no denying the huge impact SuperMemo has had on the
ﬁeld, it is not without its problems. The program is often criticized for
being buggy and diﬃcult to navigate. It only runs on Windows computers.
It is proprietary s

---

27 ===
Display Issues on macOS
Change the Video Driver
Changing the Driver From the Preferences Screen
Changing the Driver From Terminal.app
eGPUs
Monitors with Diﬀerent Resolutions
Change the Video Driver
Changing the Driver From the Preferences Screen
If you’re experiencing display issues or crashes in Anki 23.10+, you can try
changing the video driver in the preferences screen by navigating to Anki
→  Preferences and then selecting the driver from the dropdown menu.
After that it is necessary to restart Anki.
Changing the Driver From Terminal.app
Older Anki versions did not provide an option in the preferences, but
allowed you to adjust the driver by opening Terminal.app, then pasting
the following and hit Enter:
It will not print anything. You can then start Anki again.
If you wish to switch back to the default, change software to auto, or
remove that ﬁle.
echo software > ~/Library/Application\ Support/Anki2/gldriver6
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 27/273


---


## STUDYING (190 pages found)

1 ===
Introduction
Mobile Clients
This is the manual for the computer version of Anki. Separate manuals
are available for the mobile clients:
AnkiDroid Manual (Android)
AnkiMobile Manual (iPhone/iPad)
Quickstart
In a hurry? Jump straight to Getting Started.
Getting Help
Looking for help? Please see Getting Help.
Translations
Volunteers have contributed translations of this manual. The translations
may not always be up to date.
Bahasa Indonesia
Deutsch
Español
Français
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 1/273


---

2 ===
Italiano
Polski
Português Brasileiro
русский язык
Українська
اﻟﻌﺮﺑﯿﺔ
ﻓﺎرﺳﻰ
日本語
简体中文
If you would like to help translate the manual into a diﬀerent language,
please see the translation docs.
Legacy Documentation
Not on the latest version of Anki? Find archives of this manual at the
Internet Archive.
For information on old scheduler versions, see this FAQ.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 2/273


---

3 ===
Background
Active Recall Testing
Use It or Lose It
Spaced Repetition
Why Anki?
Anki is a program which makes remembering things easy. Because it is a
lot more eﬃcient than traditional study methods, you can either greatly
decrease your time spent studying, or greatly increase the amount you
learn.
Anyone who needs to remember things in their daily life can beneﬁt from
Anki. Since it is content-agnostic and supports images, audio, videos and
scientiﬁc markup, the possibilities are endless. For example:
Learning a language
Studying for medical and law exams
Memorizing names and faces of people
Brushing up on geography
Mastering long poems
Even practising guitar chords!
There are two simple concepts behind Anki: active recall testing and
spaced repetition. They are not known to most learners, despite being
well-documented in scientiﬁc literature. Understanding how these
concepts work will make you a more eﬀective learner.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 3/273


---


## DECK_OPTIONS (25 pages found)

16 ===
Antivirus/ﬁrewall software
Third-party software on your machine may prevent Anki from loading.
You can try adding an exception for Anki, or temporarily disabling your
antivirus/ﬁrewall to see if it helps.
Admin access
Some users have reported that Anki did not run for them until they right-
clicked on the Anki icon and chose “Run as administrator”. Anki stores all
of its data in your user folder, and should not need administrator
privileges, but it’s something you can try if you’ve exhausted other
options.
Multiple Anki installations present after
updating
If the update process leaves you with multiple Anki installs (such as within
C:\Program Files\Anki and C:\Program Files (x86)\Anki), they may
be left in a non-working state, and Anki may refuse to start without
showing an error message.
Try uninstalling all copies of Anki from your computer. To do this, ﬁnd
them in Windows Settings > Apps & features (or Apps > Installed apps)
and uninstall, or run uninstall.exe in each Anki program folder.
Afterward, install Anki again.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 16/273


---

38 ===
Anki not picking up GTK theme on
Gnome/Linux
You can work around this issue by explicitly telling Anki what the GTK
theme is. Run the following commands in a terminal:
Then log out and log back into your computer, and Anki should pick up
the GTK theme.
theme=$(gsettings get org.gnome.desktop.interface gtk-theme)
echo "gtk-theme-name=$theme" >> ~/.gtkrc-2.0
echo "export GTK2_RC_FILES=$HOME/.gtkrc-2.0" >> ~/.profile
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 38/273


---

43 ===
Card States
New: Cards that you have downloaded or created yourself, but have
never studied before.
Learning: Cards that were seen for the ﬁrst time recently, and are
still being learned.
Review: Cards that you have ﬁnished learning. These cards will be
shown again after their delay (interval) has elapsed. There are two
types of review cards:
Young: A young card is one that has an interval of less than 21
days.
Mature: A mature card is one that has an interval of 21 days or
greater.
Relearn: Cards that you forgot in the review stage. These cards are
returned to the relearning state to be learned again.
Decks
A deck is a group of cards. You can place cards in diﬀerent decks to study
parts of your card collection instead of studying everything at once. Each
deck can have diﬀerent settings, such as how many new cards to show
each day, or how long to wait until cards are shown again.
Decks can contain other decks, which allows you to organize decks into a
tree. Anki uses double colons (“::”) to show diﬀerent levels within the deck
tree. For example, a deck called “Chinese::Hanzi” refers to a “Hanzi” deck,
which is part of a “Chinese” deck. If you select “Hanzi”, then only the Hanzi
cards will be shown; if you select “Chinese”, then all the Chinese cards will
be shown, including the Hanzi cards.
To place decks within a tree, you can either name them with double
colons between each level, or drag and drop them within the deck list.
2026/4/10 09:30 Anki Manual
https://docs.an

---


## FSRS_ALGORITHM (25 pages found)

7 ===
Anki addresses these issues. There are free clients for Anki available on
many platforms, so struggling students and teachers with budgetary
constraints are not left out. Anki is open source, with an already
ﬂourishing library of add-ons contributed by end-users. It is multi-
platform, running on Windows, macOS, Linux/FreeBSD, and some mobile
devices. And it is considerably easier to use than SuperMemo.
Anki’s spaced repetition system is based on an older version of the
SuperMemo algorithm called SM-2. Recently, a new algorithm called FSRS
has been integrated as an alternative to the legacy SM-2 algorithm.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 7/273


---

57 ===
Answer Buttons
After the answer is shown, compare the answer you thought of with the
answer that is shown and select any of the following buttons.
Again: Select this when your answer is incorrect or when you couldn’t
recall the answer. If your answer is partially correct, you should be
strict with yourself: if it counts as a fail in a real-life context outside of
Anki, then it counts as a fail in Anki as well. You’ll typically use this
button about 5-20% of the time.
Keyboard Shortcut: 1
Hard: Select this button when your answer is correct, but you had
doubts about it or it took a long time to recall.
Keyboard Shortcut: 2
Good: Select this when your answer is correct, but it took some
mental eﬀort to recall it. When Anki is used properly, this should be
the most commonly used button. You’ll typically use this button
about 80-95% of the time.
Keyboard Shortcut: 3, Space, Enter
Easy: Select this if your answer is correct and it took no mental eﬀort
to recall it.
Keyboard Shortcut: 4
If you ﬁnd it hard to use four answer buttons, you can also use only Again
and Good buttons. Use Again for incorrect answers and use Good for
correct answers.
Each answer button shows the next time a card will be reviewed again if
you select that button. To learn about the settings that control the next
review intervals, see the topics Learning Steps, Lapses, FSRS and
Advanced in the Deck Options section.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 57/273


---

128 ===
Deck Options
Presets
Subdecks
Daily Limits
New Cards/Day
Maximum Reviews/Day
Per-Deck Daily Limits
New Cards Ignore Review Limit
Limits Start From Top
New Cards
Learning Steps
Day Boundaries
Graduating Interval
Easy Interval
Insertion Order
Lapses
Relearning Steps
Minimum Interval
Leeches
Display Order
New Card Gather Order
New Card Sort Order
New/Review Order
Interday Learning/Review Order
Review Sort Order
Burying
Audio
Timers
Internal Timer
On-screen Timer
Auto Advance
Easy Days
FSRS
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 128/273


---


## SCHEDULER (0 pages found)


## ADDONS (30 pages found)

7 ===
Anki addresses these issues. There are free clients for Anki available on
many platforms, so struggling students and teachers with budgetary
constraints are not left out. Anki is open source, with an already
ﬂourishing library of add-ons contributed by end-users. It is multi-
platform, running on Windows, macOS, Linux/FreeBSD, and some mobile
devices. And it is considerably easier to use than SuperMemo.
Anki’s spaced repetition system is based on an older version of the
SuperMemo algorithm called SM-2. Recently, a new algorithm called FSRS
has been integrated as an alternative to the legacy SM-2 algorithm.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 7/273


---

10 ===
Installing & Upgrading Anki on
Windows
Requirements
Installing
Upgrading
Add-on Compatibility
Problems
Requirements
Recent Anki releases require a computer running the 64 bit version of
Windows 10 or 11.
The last Anki release that supported Windows 7 and 8.1 was Anki
2.1.49.
The last Anki release that supported 32 bit Windows was Anki 2.1.35-
alternate.
If you’re on an old machine, you can obtain old releases from the releases
page.
Installing
To install Anki:
1. Download Anki from https://apps.ankiweb.net.
2. Save the installer to your desktop or downloads folder.
3. Double-click on the installer to run it. If you see an error message,
please see the installation issues page.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 10/273


---

11 ===
4. Once Anki is installed, double-click on the new star icon on your
desktop to start Anki.
Upgrading
If upgrading from Anki 2.1.6+, there is no need to uninstall the previous
version ﬁrst. All you need to do is close Anki if it is open, and then follow
the installation steps above. Your cards will be preserved when you
upgrade.
If upgrading from an Anki version before 2.1.6, or switching from the
standard to the alternate version or vice versa, we recommend
uninstalling the old version ﬁrst, which will remove Anki’s program data,
but not delete your card data.
If you wish to downgrade to a previous version, please make sure you
downgrade ﬁrst.
Add-on Compatibility
Some add-ons may not always work with the latest Anki release. If you
upgrade to the latest Anki version and ﬁnd an add-on you cannot live
without stops working, you can download older Anki versions from the
releases page.
Problems
If you encounter any issues when installing or starting Anki, please see
the following pages:
Installation Issues
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 11/273


---


## TROUBLESHOOTING (67 pages found)

5 ===
have spent the last two weeks telling people about how great it was,
you’re likely to still remember it in vivid detail.
The brain’s “use it or lose it” policy applies to everything we learn. If you
spend an afternoon memorizing some science terms, and then don’t
think about that material for two weeks, you’ll probably have forgotten
most of it. In fact, studies show we forget about 75% of material learned
within a 48 hour period. This can seem pretty depressing when you need
to learn a lot of information!
However, the solution is simple: review. By reviewing newly-learned
information, we can greatly reduce forgetting.
The only problem is that traditionally, reviewing has not been very
practical. If you are using paper ﬂashcards, it’s easy to ﬂick through all of
them if you only have 30 of them to review, but as the number grows to
300 or 3000, it quickly becomes unmanageable.
Spaced Repetition
The spacing eﬀect was reported in 1885 by a German psychologist called
Hermann Ebbinghaus. He observed that we tend to remember things
more eﬀectively, if we spread reviews out over time, instead of studying
multiple times in one session. Since the 1930s, there have been a number
of proposals for utilizing the spacing eﬀect to improve learning, in what
has come to be called spaced repetition.
One example was in 1972, when a German scientist called Sebastian
Leitner popularized a method of spaced repetition with paper ﬂashcards.
By separating the paper cards into a series of boxes

---

6 ===
however, as it cannot give you an exact date on which you should review
something again, and it does not work very well with material of varying
diﬃculty.
The biggest developments in the last 30 years have come from the
authors of SuperMemo, a commercial ﬂashcard program that implements
spaced repetition. SuperMemo pioneered the concept of a system that
keeps track of the ideal time to review material and optimizes itself based
on the performance of the user.
In SuperMemo’s spaced repetition system, every time you answer a
question, you tell the program how well you were able to remember it —
whether you forgot completely, made a small mistake, remembered with
trouble, remembered easily, etc. The program uses this feedback to
decide the optimal time to show you the question again. Because a
memory gets stronger each time you successfully recall it, the time
between reviews gets longer and longer — so you may see a question for
the ﬁrst time today, then 3 days later, 15 days later, 45 days later, and so
on.
This was a revolution in learning, as it meant material could be learned
and retained with the absolute minimum amount of eﬀort necessary.
SuperMemo’s slogan sums it up: with spaced repetition, you can: “forget
about forgetting”.
Why Anki?
While there is no denying the huge impact SuperMemo has had on the
ﬁeld, it is not without its problems. The program is often criticized for
being buggy and diﬃcult to navigate. It only runs on Windows computers.
It is proprietary s

---

7 ===
Anki addresses these issues. There are free clients for Anki available on
many platforms, so struggling students and teachers with budgetary
constraints are not left out. Anki is open source, with an already
ﬂourishing library of add-ons contributed by end-users. It is multi-
platform, running on Windows, macOS, Linux/FreeBSD, and some mobile
devices. And it is considerably easier to use than SuperMemo.
Anki’s spaced repetition system is based on an older version of the
SuperMemo algorithm called SM-2. Recently, a new algorithm called FSRS
has been integrated as an alternative to the legacy SM-2 algorithm.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 7/273


---


## SYNC (273 pages found)

1 ===
Introduction
Mobile Clients
This is the manual for the computer version of Anki. Separate manuals
are available for the mobile clients:
AnkiDroid Manual (Android)
AnkiMobile Manual (iPhone/iPad)
Quickstart
In a hurry? Jump straight to Getting Started.
Getting Help
Looking for help? Please see Getting Help.
Translations
Volunteers have contributed translations of this manual. The translations
may not always be up to date.
Bahasa Indonesia
Deutsch
Español
Français
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 1/273


---

2 ===
Italiano
Polski
Português Brasileiro
русский язык
Українська
اﻟﻌﺮﺑﯿﺔ
ﻓﺎرﺳﻰ
日本語
简体中文
If you would like to help translate the manual into a diﬀerent language,
please see the translation docs.
Legacy Documentation
Not on the latest version of Anki? Find archives of this manual at the
Internet Archive.
For information on old scheduler versions, see this FAQ.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 2/273


---

3 ===
Background
Active Recall Testing
Use It or Lose It
Spaced Repetition
Why Anki?
Anki is a program which makes remembering things easy. Because it is a
lot more eﬃcient than traditional study methods, you can either greatly
decrease your time spent studying, or greatly increase the amount you
learn.
Anyone who needs to remember things in their daily life can beneﬁt from
Anki. Since it is content-agnostic and supports images, audio, videos and
scientiﬁc markup, the possibilities are endless. For example:
Learning a language
Studying for medical and law exams
Memorizing names and faces of people
Brushing up on geography
Mastering long poems
Even practising guitar chords!
There are two simple concepts behind Anki: active recall testing and
spaced repetition. They are not known to most learners, despite being
well-documented in scientiﬁc literature. Understanding how these
concepts work will make you a more eﬀective learner.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 3/273


---


## MEDIA (67 pages found)

3 ===
Background
Active Recall Testing
Use It or Lose It
Spaced Repetition
Why Anki?
Anki is a program which makes remembering things easy. Because it is a
lot more eﬃcient than traditional study methods, you can either greatly
decrease your time spent studying, or greatly increase the amount you
learn.
Anyone who needs to remember things in their daily life can beneﬁt from
Anki. Since it is content-agnostic and supports images, audio, videos and
scientiﬁc markup, the possibilities are endless. For example:
Learning a language
Studying for medical and law exams
Memorizing names and faces of people
Brushing up on geography
Mastering long poems
Even practising guitar chords!
There are two simple concepts behind Anki: active recall testing and
spaced repetition. They are not known to most learners, despite being
well-documented in scientiﬁc literature. Understanding how these
concepts work will make you a more eﬀective learner.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 3/273


---

14 ===
Windows startup issues
No error, but app does not appear
Windows updates
Windows 7/8
Video driver issues
Multiple displays
Antivirus/ﬁrewall software
Admin access
Multiple Anki installations present after updating
Debugging
If all else fails
No error, but app does not appear
If you start Anki and it fails to appear, without any error message, you can
try the following:
Disconnect multiple/external displays.
Install the latest Anki version.
Adjust your decimal separator, if it is not a period.
Install the old 2.1.35-alternate build of Anki.
Windows updates
When starting Anki, you may receive a message like the following:
Error loading Python DLL
The program can’t start because api-ms-win…. is missing
Failed to execute script runanki
Failed to execute script pyi_rth_multiprocessing
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 14/273


---

15 ===
Failed to execute script pyi_rth_win32comgenpy
These errors are usually because your computer is missing a Windows
update or Windows library.
Please open Windows update, and ensure your system has all updates
installed. If any needed to be installed, please restart your device after
installing.
Windows 7/8
On Windows 7/8, you may need to manually install extra updates. Please
try:
https://www.microsoft.com/en-us/download/details.aspx?id=48234
https://aka.ms/vs/15/release/vc_redist.x64.exe
http://www.catalog.update.microsoft.com/Search.aspx?q=kb4474419
http://www.catalog.update.microsoft.com/Search.aspx?q=kb4490628
Video driver issues
Please see display issues.
Multiple displays
If you get a LoadLibrary failed with error 126, this may be caused by the
toolkit Anki is built on having trouble with multiple displays.
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 15/273


---


## PREFERENCES (0 pages found)


## IMPORTING (45 pages found)

36 ===
Blank Main Window
Some Linux distros have recently updated glibc. Recent versions break
the web toolkit that Anki is built on, causing Anki’s main window to appear
blank.
There are two ways to work around this:
1. Install the latest Qt6 version of Anki, which uses an updated toolkit:
https://apps.ankiweb.net
2. Use one of the workarounds posted on the following threads:
https://forums.ankiweb.net/t/another-blank-main-window-solution-
for-linux/32835
https://forums.ankiweb.net/t/please-use-ﬁle-import-popup-on-
startup/14695
https://forums.ankiweb.net/t/setting-disable-seccomp-ﬁlter-sandbox-
by-default-on-linux/13765
https://forums.ankiweb.net/t/fedora-35-and-anki-2-1-47-updates-
with-blank-anki-window/13431/11
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 36/273


---

49 ===
diﬀerent decks. When you add notes using the Add window, you can
select what note type to use and what deck to use, and these choices are
completely independent of each other. You can also change the note type
of notes after you’ve already created them.
Collection
Your collection is all the material stored in Anki: your cards, notes, decks,
note types, deck options, and so on.
Shared Decks
You can watch a video about Shared Decks and Review Basics on
YouTube.
The easiest way to get started with Anki is to download a deck of cards
someone else has shared:
1. Click the Get Shared button at the bottom of the deck list.
2. When you’ve found a deck you’re interested in, click the Download
button to download a deck package.
3. Double-click the downloaded package to import it into Anki, or go to
File > Import.
Note: It’s not currently possible to add shared decks directly to your
AnkiWeb account. You need to ﬁrst import them to the desktop app,
AnkiMobile, or AnkiDroid, then synchronize to upload the decks to
AnkiWeb.
Creating your own deck is the most eﬀective way to learn a complex
subject. Subjects like languages and the sciences can’t be understood
simply by memorizing facts — you need explanation and context to learn
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 49/273


---

68 ===
To change the order in which the ﬁelds appear in this dialog and the add
notes dialog, you can use the reposition button, which asks for the
numerical position you want the ﬁeld to have. So if you want to change a
ﬁeld to be the new ﬁrst ﬁeld, enter “1”.
Alternatively you can also drag and drop the ﬁeld names to reorder them.
To do that, use your mouse or ﬁnger to drag the ﬁeld to the desired
position. An indicator will show you where the ﬁeld will be moved to.
Do not use “Tags”, “Type”, “Deck”, “Card”, or “FrontSide” as ﬁeld names, as
they are special ﬁelds and will not work properly.
The options at the bottom of the screen allow you to edit various
properties of the ﬁelds to be used when adding and editing the cards.
This is not where you customize what appears on your cards when
reviewing; for that, please see templates.
Editing Font allows you to customize the font and size used when
editing notes. This is useful if you want to make unimportant
information smaller, or increase the size of non-Latin characters
which are hard to read. The changes you make here do not aﬀect
how cards appear when reviewing: to do that, please see the
templates section. If you have enabled the “type in the answer”
function, however, the text you type will use the font size deﬁned
here. (For information about how to change the actual font face when
typing the answer, please see the checking your answer section.)
Sort by this ﬁeld…  tells Anki to show this ﬁeld in the Sort Field
column of

---


## EXPORTING (31 pages found)

38 ===
Anki not picking up GTK theme on
Gnome/Linux
You can work around this issue by explicitly telling Anki what the GTK
theme is. Run the following commands in a terminal:
Then log out and log back into your computer, and Anki should pick up
the GTK theme.
theme=$(gsettings get org.gnome.desktop.interface gtk-theme)
echo "gtk-theme-name=$theme" >> ~/.gtkrc-2.0
echo "export GTK2_RC_FILES=$HOME/.gtkrc-2.0" >> ~/.profile
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 38/273


---

55 ===
When you click on a deck, it will become the “current deck”, and Anki will
change to the study screen. You can return to the deck list at any time by
clicking on “Decks” at the top of the main window. (You can also use the
Study Deck action in the menu to select a new deck from the keyboard, or
you can press the S key to study the currently selected deck.)
You can click the gears button to the right of a deck to rename or delete
the deck, change its options, or export it.
Study Overview
After clicking on a deck to study, you’ll see a screen that shows you how
many cards are due today. This is called the “deck overview” screen:
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 55/273


---

94 ===
show the ruby text, while the kanji ﬁlter removes the ruby text entirely.
Raw Text Field Filter Rendered Text
日本語 [ にほんご ] {{furigana:MyField}}日本語
 に ほ ん ご
日本語 [ にほんご ] {{kana:MyField}} にほんご
日本語 [ にほんご ] {{kanji:MyField}} 日本語
These names are, again, borrowed from Japanese. The term kana
represents the phonetic system used to describe how words are
pronounced, whereas the term kanji represents its Chinese characters.
Media & LaTeX
Anki does not scan templates for media references, because it is slow to
do so. This has implications for including media on the template.
Static Sounds/Images
If you wish to include images or sounds on your cards that are the same
for every card (e.g. a company logo at the top of each card):
1. Rename the ﬁle so it starts with an underscore, e.g “_logo.jpg”. The
underscore tells Anki that the ﬁle is used by the template and it
should be exported when sharing the deck.
2. Add a reference to the media on your front or back template, like:
<img src="_logo.jpg">
2026/4/10 09:30 Anki Manual
https://docs.ankiweb.net/print.html 94/273


---
