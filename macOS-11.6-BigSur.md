Setting Up macOS Big Sur
========================

System Preferences > General
----------------------------

* Appearance: `Auto`
* Sidebar icon size: `Large`

> For `Command + N` and `Command + T` to always work as expected:

* Prefer tabs: `never`

> To restore full screen windows:

* Uncheck: Close windows when quitting an app

System Preferences > Desktop & Screen Saver
-------------------------------------------

* Big Sur: `Dynamic`

System Preferences > Dock & Menu Bar
------------------------------------

* Magnification: `Max`

`Sound`:

* Show in Menu Bar: `always`

`Battery`:

* Show Percentage

`Clock`:

* Use a 24-hour clock

`Spotlight`:

* Uncheck: Show in Menu Bar

System Preferences > Siri
-------------------------

* Enable Ask Siri
* Uncheck: Show Siri in menu bar

System Preferences > Spotlight
------------------------------

`Privacy`:

* Prevent Spotlight from searching these locations: `tmp`

System Preferences > Notifications
----------------------------------

`Do Not Disturb`:

* From `22:00` to `07:00`

When Do Not Disturb is turned on:

* Allow repeated calls

System Preferences > Internet accounts
--------------------------------------

Add email accounts.

System Preferences > Touch ID
-----------------------------

* Add right index, right thumb, and left index fingers.

System Preferences > User & Groups
----------------------------------

`Current User`:

* Drag & Drop a picture to change
* Click the lock to make changes

`Guest User`:

* Uncheck: Allow guests to login to this computer

`Login Options`:

* Display login window as: `List of users`

System Preferences > Security & Privacy
---------------------------------------

`General`:

> To quickly switch display back on without a password:

* Require password `5 seconds` after sleep or screen saver begins

System Preferences > Network
----------------------------

Select the correct network and:

* Automatically join this network

System Preferences > Printers & Scanners
----------------------------------------

Setup printers.

System Preferences > Keyboard
-----------------------------

`Keyboard`:

* Key Repeat: `Fast`
* Delay Until Repeat: `Short`
* Turn keyboard backlight off after: `10 secs of inactivity`
* Press Fn key to: `Start Dicttion (Press Fn Twice)`
* Press and hold Fn key to: `Expand Control Strip`
* Customize Control Strip: `Brightness Slider`, `Volume Slider`, `Mute`, `Play/Pause`
* Expanded Control Strip: `Dafault`, remove `Siri`, add `Do Not Disturb`

`Text`:

* Spelling: `Set Up...`

`Input Sources`:

* `U.S.`
* `Canadian French - CSA`
* `Ukrainian - PC`
* `Polish - Pro`
* `Russian - PC`

`Shortcuts` > `Mission Control`:

* Uncheck: Show Desktop: `F11`

`Shortcuts` > `Function Keys`:

* Add: `Terminal`
* Add: `Visual Studio Code`
* Add: `/System/Library/Frameworks/Tk.framework/Versions/Current/Resources/Wish.app`
* Add: `/usr/local/Cellar/git/<VERSION>/share/git-gui/lib/Git Gui.app`

Note: press `Command + Shift + .` to show hidden files in the open file dialog.

> To use keyboard in dialogs:

* Use keyboard navigation to move focus between controls

`Dictation`:

* Dictation: `On`
* Language: `Add Language...`

System Preferences > Trackpad
-----------------------------

`Point & Click`:

* Tap to click
* Tracking speed: `3/4`

System Preferences > Displays
-----------------------------

`Display`:

* Resolution: `Scaled`
* Second Larger Text

`Night Shift`:

* Schedule: `Sunset to Sunrise`

System Preferences > Time Machine
---------------------------------

`Options` dialog:

* Exclude these items from backups: `~/tmp`

System Preferences > Language & Region
--------------------------------------

At the very end, remove all the languages but `English`

Desktop Preferences
-------------------

* Right Click > `Use Stacks`

Keep on Dock:

* `Calculator`
* `Terminal`

Remove from Dock:

* `Contacts`
* `Apple TV`
* `Podcasts`
* `App Store`
* `System Preferences`
* `Keynote`
* `Numbers`
* `Pages`

Finder Preferences
------------------

* Right click on `Documents` > Add to Dock
* Go > `Home`, File > Add to sidebar
* Press `Command + Shift + Period` to show hidden files

Safari Preferences
------------------

`Advanced`:

> For `Responsive Design Mode` (`Control + Command + R`):

* Show Develop menu in menu bar

> To always show Tab Bar with pinned tabs:

* Open a new window: `Command + N`
* View > Show Tab Bar

> To show link URL:

* View > Show Status Bar

Dictionary Preferences
----------------------

* Uncheck: UK
* Uncheck: UK Thesaurus
* German
* german-English
* French
* French-English
* Polis-English
* Russian
* Russian-English

Wikipedia Languages:

* English
* Deutsch
* Fraçais
* Polski
* Русский
* Українська

Homebrew Cask Applications
--------------------------

```zsh
brew install --cask google-chrome docker meld visual-studio-code blender gimp inkscape vlc
```

Casks for Development:

* Docker: `docker`
* Git GUI Merge Tool: `meld`
* Visual Studio Code IDE (vscode): `visual-studio-code`

Graphics Casks:

* Blender (3D graphics): `blender`
* GIMP (raster graphics): `gimp`
* Inkscape (vector graphics): `inkscape`
* VLC Media Player: `vlc`

Homebrew Applications
---------------------

```zsh
brew install aspell coreutils gawk mc p7zip watch wget zsh-completions clang-format cloc git git-gui htop python rustup-init shfmt ffmpeg imagemagick potrace
```

General formulas:

* Spell Checker: `aspell`
* GNU File, Shell, and Text utilities: `coreutils`
* GNU AWK: `gawk`
* Midnight Commander (File Manager): `mc`
* 7zip: `p7zip`
* Execute a Program Periodically: `watch`
* Network Downloader: `wget`
* Completions for zsh: `zsh-completions`

Formulas for Development:

* C/C++ Language Formatter: `clang-format`
* Count Lines of Code: `cloc`
* Version Control System: `git`
* UI for the git: `git-gui`
* Interactive Process Viewer: `htop`
* Python Version 3: `python`
* Rust Toolchain Installer: `rustup-init`
* Shell Language Formatter: `shfmt`

Graphics formulas:

* Video Convertor: `ffmpeg`
* Batch Image Manipulation: `imagemagick`
* Image Tracing Tool: `potrace`

Rust Language
-------------

```zsh
brew install rustup-init
rustup-init --default-toolchain nightly
mkdir ~/.zfunc
rustup completions zsh > ~/.zfunc/_rustup
rustup completions zsh cargo > ~/.zfunc/_cargo
```

Nix
---

```zsh
curl -L https://nixos.org/nix/install | sh -s -- --darwin-use-unencrypted-nix-store-volume
```

Visual Studio Code (vscode)
---------------------------

To install VS Code:

```zsh
brew cask install visual-studio-code
```

Extensions to install:

* `C/C++`
* `Code Spell Checker`
* `GitLens`
* `JSON5 syntax`
* `Hide Gitignored`
* `Markdown All in One`
* `Markdownlint`
* `Nix Environment Selector`
* `pre-commit-vscode`
* `Prettier - Code formatter`
* `Python`
* `Remote - SSH`
* `Rust`
* `rust-analyzer`
* `shell-format`
* `Terminal`
* `TODO Highlight`
* `vscode-proto3`
* `YAML`

Settings:

```javascript
{
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 100,
    "editor.rulers": [72, 100],
    "editor.fontSize": 15,
    "window.zoomLevel": -1,
    "editor.renderWhitespace": "boundary",
    "editor.wordWrap": "on",
    "editor.minimap.size": "fill",
    "editor.minimap.showSlider": "always",
    "workbench.editor.tabCloseButton": "left",
    "zenMode.centerLayout": false,
    "rust-analyzer.lens.enable": false,
    "gitlens.codeLens.enabled": false,
}
```

VS Code also requires few Homebrew applications to be installed:

```zsh
brew install buildifier clang-format git python shfmt
```

Terminal Preferences
--------------------

`General`:

* On startup, open new window with profile: `Homebrew`

`Profiles`:

* Select `Homebrew` and click `Default`

`Profiles` > `Homebrew` > `Text`:

* Font > Change... > Size: `18pt`

`Profiles` > `Homebrew` > `Window`:

* Rows: `43`

`Profiles` > `Homebrew` > `Shell`:

* When the shell exits: `Close if the shell exited cleanly`

`Profiles` > `Homebrew` > `Keyboard`:

* Use Option as Meta key
* Double click `F11` key to edit > Key: `F1` Modifier: `Shift`
* Repeat for `F12-F20` keys

Terminal Profiles
-----------------

File `~/.zshrc`:

```zsh
alias ll="ls -GFhla"
alias ls="ls -GFha"
alias mc="mc -d -S gotar"
alias mcedit="mcedit -d -S gotar"
alias top="top -o cpu" # for macOS

export PATH="${HOME}/bin:/usr/local/sbin:${PATH}"
export EDITOR="mcedit"

fpath+=/usr/local/share/zsh-completions
fpath+=~/.zfunc
autoload -Uz compinit
compinit
```

> To fix `zsh compinit: insecure directories` message:

```zsh
compaudit | xargs chmod g-w
```

Midnight Commander (mc) Preferences
-----------------------------------

`Options > Layout`:

* Uncheck: Menubar visible
* Uncheck: Hintbar visible

`Editor > Options > General`:

* Uncheck: Confirm before saving

git Preferences
---------------

```zsh
git config --global user.name "Andriy Berestovskyy"
git config --global user.email "berestovskyy@gmail.com"
```

SSH Preferences
---------------

* Generate SSH key pair: `ssh-keygen -C a@hostname`
* To use for some hosts different user name add to `.ssh/config` the following:

```ssh
Host host.com
    User name
```

GitHub Preferences
------------------

* Generate SSH key pair as described above.
* Open https://github.com
* Select `Settings > SSH and GPG keys` then `New SSH key`
* Dump public key:
   ```zsh
   cat ~/.ssh/id_rsa.pub
   ```
* Paste the key into GitHub.

Mail Preferences
----------------

`Fonts & Colors`:

* All font sizes: `14`

`Composing`:

* Message Format: `Plain Text`

Symbolic Links Installation
---------------------------

```zsh
cd && ln -s /usr/local
cd && ln -s /usr/local/etc
cd && ln -s Library/Fonts
cd && mkdir tmp
cd ~/Desktop && ln -s ../tmp
cd ~/Documents && ln -s ../tmp
cd ~/Downloads && ln -s ../tmp
sudo chmod g-w /usr/local/share
```

Preview Preferences
-------------------

`Images`:

* Open all files in one window

Messages Preferences
--------------------

`iMessage`:

* Enable messages in iCloud
* You can be reached for messages at
* Start new conversations from

FaceTime Preferences
--------------------

`Settings`:

* Enable messages in iCloud
* You can be reached for FaceTime at
* Start new calls from
