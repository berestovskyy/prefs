Setting Up macOS Catalina
=========================

System Preferences > General
----------------------------

* Appearance: `Auto`
* Accent color: `Green`
* Sidebar icon size: `Large`

> To restore full screen windows:

* Uncheck: Close windows when quitting an app

System Preferences > Desktop & Screen Saver
-------------------------------------------

* Catalina: `Dynamic`

System Preferences > Dock
-------------------------

* Magnification: `Max`

For `Command + N` and `Command + T` to always work as expected:

* Prefer tabs when opening documents: `Manually`

System Preferences > Mission Control
------------------------------------

> To switch display off while rendering:

* Hot Corners > bottom-left: `Put Display to Sleep`

System Preferences > Siri
-------------------------

* Keyboard Shortcut: `Press Fn (Function) Space`
* Keyboard Shortcut: `Hold Command Space`
* Language: `Russian`
* Siri Voice: `Female`
* Voice Feedback: `Off`
* Uncheck: Show Siri in menu bar

> For `MacBook Pro 15"`:

* Listen for "Привет, Siri"
* Allow Siri when locked

System Preferences > Notifications
----------------------------------

`Do Not Disturb` panel:

* From `22:00` to `08:00`
* When the display is sleeping

System Preferences > Internet accounts
--------------------------------------

Add email accounts.

System Preferences > Touch ID
-----------------------------

* Add right index, right thumb, and left index fingers.

System Preferences > User & Groups
----------------------------------

Current User panel:

* Drag & Drop a picture to change
* Click the lock to make changes

Guest User panel:

* Uncheck: Allow guests to login to this computer

Login Options panel:

* Show fast user switching menu as: `Account Name`

System Preferences > Security & Privacy
---------------------------------------

`General` tab:

> To quickly switch display back on without a password:

* Require password `5 seconds` after sleep or screen saver begins

System Preferences > Network
----------------------------

Select the correct network and:

* Automatically join this network

System Preferences > Sound
--------------------------

* Show volume in menu bar

System Preferences > Printers & Scanners
----------------------------------------

Setup printers.

System Preferences > Keyboard
-----------------------------

`Keyboard` tab:

* Key Repeat: `Fast`
* Delay Until Repeat: `Short`
* Turn keyboard backlight off after: `10 secs of inactivity`
* Show keyboard and emoji viewers in menu bar

> To use function keys in VS Code and MC:

* Use F1, F2, etc. keys as standard function keys

> For `MacBook Pro 15"`:

* Touch Bar shows: `App Controls` + `Show control strip`
* Press Fn key to: `Expand Control Strip`
* Customize control strip: `Volume Slider`, `Play/Pause`, `Mute`, `Screen Lock`

Note: to use functional keys in some applications, add them in
`Shortcuts` tab > `Function Keys` panel (see below).

`Text` tab:

* Spelling: `Set Up...`

`Input Sources` tab:

* `U.S.`
* `Canadian French - CSA`
* `Ukrainian - PC`
* `Polish - Pro`
* `Russian - PC`

`Shortcuts` tab > `Input Sources` panel:

* Select the previous input source: `^Space`

`Shortcuts` tab > `Mission Control` panel:

* Uncheck: Show Desktop: `F11`

> For `MacBook Pro 15"`:

`Shortcuts` tab > `Function Keys` panel:

* Add: `Terminal`
* Add: `Visual Studio Code`
* Add: `Blender`
* Add: `/System/Library/Frameworks/Tk.framework/Versions/Current/Resources/Wish.app`
* Add: `/usr/local/Cellar/git/<VERSION>/share/git-gui/lib/Git Gui.app`

Note: press `Command + Shift + .` to show hidden files in the open file dialog.

> To use keyboard in dialogs:

* Use keyboard navigation to move focus between controls

`Dictation` tab:

* Dictation: `On`
* Language: `Add Language...`

System Preferences > Trackpad
-----------------------------

`Point & Click` tab:

* Tap to click
* Tracking speed: `3/4`

System Preferences > Displays
-----------------------------

`Display` tab:

* Resolution: `Scaled`
* Larger Text

`Night Shift` tab:

* Schedule: `Sunset to Sunrise`

System Preferences > Energy Saver
---------------------------------

`Power Adapter` tab:

> To switch display off while rendering:

* Prevent computer from sleeping automatically when the display is off

System Preferences > Date & Time
--------------------------------

`Clock` tab:

* Date options: `Show date`

System Preferences > Sharing
----------------------------

* Computer Name

System Preferences > Time Machine
---------------------------------

* Show Time Machine in menu bar

`Options` dialog:

* Exclude these items: `~/tmp`

System Preferences > Language & Region
--------------------------------------

At the very end, remove all the languages but `English (US)`

Desktop Preferences
-------------------

* Right Click > `Use Stacks`

Keep on Dock:

* `Calculator`
* `Terminal`

Remove from Dock:

* `Siri`
* `Contacts`
* `Pages`
* `Numbers`
* `Keynote`
* `System Preferences`
* `Apple TV`
* `Podcasts`
* `App Store`

Battery status in menu bar:

* Show percentage

Finder Preferences
------------------

* Right click on `Documents` > Add to Dock
* Right click on `Desktop` > Add to Dock
* Go > `Computer`, File > Add to sidebar
* Go > `Home`, File > Add to sidebar
* Press `Command + Shift + Period` to show the hidden files

Safari Preferences
------------------

`General` tab:

* Safari opens with: `All windows from last session`
* New windows open with: `Top Sites`
* New tabs open with: `Top Sites`

`Advanced` tab:

> For `Responsive Design Mode` (`Control + Command + R`):

* Show Develop menu in menu bar

To always show Tab Bar with pinned tabs:

* Open a new window: `Command + N`
* View > Show Tab Bar

To show link URL:

* View > Show Status Bar

The options will persist across the Safari reloads.

Dictionary Preferences
----------------------

* Uncheck: British
* Uncheck: British Thesaurus
* French
* French-English
* Russian
* Russian-English

Wikipedia Languages:

* English
* Fraçais
* Polski
* Русский
* Українська

App Store Applications
----------------------

* `XCode`

Homebrew Cask Applications
--------------------------

Homebrew installation (see <http://brew.sh>):

```zsh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

To install all Cask applications:

```zsh
brew cask install firefox google-chrome adoptopenjdk docker meld minikube osxfuse virtualbox visual-studio-code wireshark xquartz blender gimp inkscape vlc viscosity
```

General Casks:

* Firefox (browser): `firefox`
* Google Chrome (browser): `google-chrome`

Casks for Development:

* Adopt OpenJDK (for Closure compiler): `adoptopenjdk`
* Docker: `docker`
* Git GUI Merge Tool: `meld`
* Minikube (local Kubernetes): `minikube`
* FUSE for macOS (for sshfs): `osxfuse`
* Oracle VirtualBox (virtual machine hypervisor): `virtualbox`
* Visual Studio Code IDE (vscode): `visual-studio-code`
* Network traffic analyzer: `wireshark`
* XQuartz (X11 Server): `xquartz`

Graphics Casks:

* Blender (3D graphics): `blender`
* GIMP (raster graphics): `gimp`
* Inkscape (vector graphics): `inkscape`
* VLC Media Player: `vlc`

Other Casks:

* OpenVPN Client: `viscosity`

Homebrew Applications
---------------------

Homebrew installation (see <http://brew.sh>):

```zsh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

To install all applications:

```zsh
brew install aspell gawk mc p7zip watch wget zsh-completions buildifier clang-format cloc closure-compiler cmake git go htop kubernetes-cli kubernetes-helm python rust shfmt sshfs wireshark ffmpeg imagemagick az
```

General formulas:

* Spell Checker: `aspell`
* GNU AWK: `gawk`
* Midnight Commander (File Manager): `mc`
* 7zip: `p7zip`
* Execute a Program Periodically: `watch`
* Network Downloader: `wget`
* Completions for zsh: `szh-completions`

Formulas for Development:

* Bazel Files Formatter: `buildifier`
* C/C++ Language Formatter: `clang-format`
* Count Lines of Code: `cloc`
* Google Javascript Compiler: `closure-compiler`
* CMake Build System: `cmake`
* Version Control System: `git`
* Go Language: `go`
* Interactive Process Viewer: `htop`
* Kubernetes kubectl Tool: `kubernetes-cli`
* Kubernetes Package Manager: `kubernetes-helm`
* Python Version 3: `python`
* Rust Language: `rust`
* Shell Language Formatter: `shfmt`
* SSH File System: `sshfs`
* Network Traffic Analyzer: `wireshark`

Graphics formulas:

* Video Convertor: `ffmpeg`
* Batch Image Manipulation: `imagemagick`

Cloud formulas:

* Azure CLI: `az`

> To fix the "invalid object doesn't have additional properties" error:

```zsh
rm /usr/local/bin/kubectl
brew link --overwrite kubernetes-cli
```

Visual Studio Code (vscode)
---------------------------

To install VS Code:

```zsh
brew cask install visual-studio-code
```

Extensions to install:

* `Bazel`
* `C/C++`
* `CMake`
* `Code Spell Checker`
* `CodeLLDB`
* `Docker`
* `Edit csv`
* `GitLens`
* `hide-gitignored`
* `Kubernetes`
* `Markdown All in One`
* `Markdownlint`
* `Python`
* `Rainbow CSV`
* `Rust (rls)`
* `shell-format`
* `YAML`

Settings:

```javascript
{
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 100,
    "editor.dragAndDrop": false,
    "editor.rulers": [72, 80],
    "editor.fontSize": 16,
    "editor.renderWhitespace": "boundary",
    "C_Cpp.clang_format_style": "Google",
    "python.pythonPath": "/usr/local/bin/python3",
    "zenMode.centerLayout": false,
    "window.zoomLevel": 1,
    "terminal.integrated.scrollback": 10000,
}
```

Keyboard shortcuts:

```javascript
[
    {
        "key": "shift+cmd+a",
        "command": "workbench.action.tasks.test"
    }
]
```

VS Code also requires few Homebrew applications to be installed:

```zsh
brew install buildifier clang-format git python shfmt
```

To install `pylint`:

```zsh
sudo easy_install pip
sudo pip install pylint
```

Terminal Preferences
--------------------

`Profiles` tab:

* Select Homebrew panel and click `Default`

`Text` tab:

* Font > Change... > Size: `18pt`

`Window` tab:

* Rows: `43`

`Shell` tab:

* When the shell exits: `Close if the shell exited cleanly`

`Keyboard` tab:

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

export PATH="${HOME}/bin:${PATH}"
export EDITOR="mcedit"
export LC_ALL="en_US.UTF-8"

fpath=(/usr/local/share/zsh-completions $fpath)
autoload -Uz compinit
compinit
```

Midnight Commander (mc) Preferences
-----------------------------------

Ubuntu: `Options > Configuration`:

* Use internal edit

`Options > Layout`:

* Uncheck: Menubar visible
* Uncheck: Hintbar visible

`Options > Confirmation...`:

* Uncheck: Confirmation|Exit

`Options > Appearance`:

* Skin: `gotar`

`Options > Display bits`:

* Input / display codepage: `UTF-8`

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

`Composing` tab:

* Message Format: `Plain Text`

`Fonts & Colors` tab:

* Font size: `14`

Docker Installation and Preferences
-----------------------------------

Install Docker:
```zsh
brew cask install docker
```

Docker Preferences > Advanced

* Memory: `8GB`
* Swap: `4GB`

Symbolic Links Installation
---------------------------

```zsh
cd && ln -s /usr/local
cd && ln -s /usr/local/etc
cd && ln -s Library/Fonts
cd && mkdir tmp
cd Desktop && ln -s ../tmp
cd Documents && ln -s ../tmp
cd Downloads && ln -s ../tmp
```

Photos Preferences
------------------

`iCloud` tab:

* iCloud Photos
* Optimize Mac Storage

Preview Preferences
-------------------

`Images` tab:

* Open all files in one window

Tools Installation
------------------

* TODO: tools repo: copy try, passwordless to ~/bin
