# keyboard shortcuts & productivity tools 

## keyboard shortcuts & configurations

### 1. MacOS

<https://support.apple.com/en-us/HT201236>

#### Function keys

By default, F1-F12 are special function keys, like adjust screen brightness. You are required to press Fn at the same time, when you need input F1-F12(like IntelliJ IDEA shortcuts). It's not so convenient for developers.

To avoid pressing Fn: go to `System Preferences` > `Keyboard`，select `Use all F1, F2, etc. keys as standard function keys` in Keyboard tab.

#### Change `click` of Trackpad to `Tap`

By default Trackpad is triggered by click, but you can change it to tap.

Goto `System Preferences` > `Trackpad`，check `Tap to click` in `Point & Click` tab.

#### Dock position

Dock comes at the bottom of screen as default, but as the resolution is 16:10, we'd better move it to left or right of screen to gain more vertical space.

#### Efficient Cursor

By default, cursor has pretty slow blinking and moving speed. When you need delete a large paragraphs of text by pressing the backspace, you are probably wasting your time. Even you hold the backspace key hardly, the cursor is still as slow as a snail.

Speed up cursor: Go to `System Preferences` > `Keyboard`, move `Key Repeat` and `Delay Until Repeat` slidebars to rightmost under Keyboard tab. Enjoy your speed now!

### 2. Chrome 

<https://support.google.com/chrome/answer/157179?hl=en&co=GENIE.Platform%3DDesktop>

### 3. IntelliJ IDEA

<https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf>

### 4. Github

<https://docs.github.com/en/get-started/using-github/keyboard-shortcuts>

### 5. iTerm

<https://gist.github.com/squarism/ae3613daf5c01a98ba3a>

#### use `⌥ ←` / `⌥ →` to move by words

In iTerm, first go to `Preferences` > `Profiles` > `Keys` > `General`, you need to set your left/right option key to act as an escape character. Then go to `Key Mappings`, you can either change the current shortcut for `⌥ ←` / `⌥ →` or create a new one, in the profile shortcut keys, with the following settings:

Keyboard Shortcut: `⌥ ←` / `⌥ →`

Action: Send Escape Sequence

Esc+: b(for `⌥ ←`) / f(for `⌥ →`)

***

## productivity tools

### 1. Raycast

Raycast provides a much richer feature set compared to those launchers. On top of searching local apps and files, it can be your clipboard manager, text expander, window manager, command palette for all apps and much more. Raycast provides much deeper and more native integrations to third party services. You can install extensions for Jira, GitHub, and Google Workspace, amongst others from the Store and control them without ever opening a browser.

Raycast’s command line inspired user interface goes beyond searching data. List and detail views provide quick access to important information. Forms make it easy to create new content such as Jira issues, and the Action Panel is used to perform actions such as merging a GitHub pull request. We concentrate on providing a fluid UX throughout the app.

Raycast can be extended to tailor the experience even further with Script Commands and custom extensions which can be built with our flexible API. You can share all that within teams or communities.

Installation:

    brew install --cask raycast

### 2. Notion

Notion is a note-taking software platform designed to help members of companies or organizations manage their knowledge for greater efficiency and productivity.

Installation:

<https://www.notion.so/desktop>

### 3. iShot

iShot is an excellent, full-featured area screenshot, window screenshot, multi-window screenshot, long screenshot, shell screenshot, time-lapse screenshot, quick annotation, texture, color picking, screen recording, audio recording, OCR, screenshot translation tool on Mac .

Installation: 

App Store

### 4. Oh my zsh

Oh My Zsh is a delightful, open source, community-driven framework for managing your Zsh configuration. It comes bundled with thousands of helpful functions, helpers, plugins, themes, and a few things that make you shout...

Installation: 

via curl:

    sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

via wget:

    sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"

### 5. Homebrew & Homebrew cask

Homebrew is a free and open-source software package management system that simplifies the installation of software on Apple's operating system, macOS, as well as Linux.

Homebrew Cask extends Homebrew and brings its elegance, simplicity, and speed to the installation and management of GUI macOS applications such as Atom and Google Chrome.

To start using Homebrew Cask, you just need Homebrew installed.

Installation: 

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

### 6. The Silver Searcher

The Silver Searcher is a free and open source, cross platform source code searching tool similar to ack (a grep-like tool for programmers) but faster.

Installation: 

    brew install the_silver_searcher

### 7. Sourcetree

A free Git client for Windows and Mac

Sourcetree simplifies how you interact with your Git repositories so you can focus on coding. Visualize and manage your repositories through Sourcetree's simple Git GUI.

Installation: 

<https://www.sourcetreeapp.com/>

### 8. CheatSheet

Cheatsheet is used to quick reference of keyboard shortcuts in each application and cheatSheet works hand in hand with CustomShortcuts from my friends at Houdah Software. This way, the shortcuts can be edited directly in CustomShortcuts with a click on the pen symbol.

Installation: 

<https://www.mediaatelier.com/CheatSheet/>

### 9. F.lux

f.lux makes your computer screen look like the room you're in, all the time. When the sun sets, it makes your computer look like your indoor lights. In the morning, it makes things look like sunlight again.

Installation: 

<https://justgetflux.com/>

### 10. Sublime Text

Sublime Text is a shareware cross-platform source code editor. It natively supports many programming languages and markup languages. Users can expand its functionality with plugins, typically community-built and maintained under free-software licenses. 

Installation: 

<https://www.sublimetext.com/>

***

## Reference

<https://github.com/macdao/ocds-guide-to-setting-up-mac>

