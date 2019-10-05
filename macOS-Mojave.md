Setting Up macOS Mojave
=======================

1. Select the `Dark Theme`
2. Update macOS and applications

System Preferences > General
----------------------------

* Accent color: `green`
* Sidebar icon size: `Large`

> To restore full screen windows:

* Uncheck: Close windows when quitting an app

System Preferences > Dock
-------------------------

* Magnification: `3/4`

For `Command + N` and `Command + T` to always work as expected:

* Prefer tabs when opening documents: `Manually`

> For `MacBook Pro 15"`:

* Magnification: `Max`

System Preferences > Mission Control
------------------------------------

> To switch display off while computing:

* Hot Corners > bottom-left: `Put Display to Sleep`

System Preferences > Security & Privacy
---------------------------------------

`General` tab:

> To quickly switch display back on without a password:

* Require password `5 seconds` after sleep or screen saver begins

System Preferences > Notifications
----------------------------------

`Do Not Disturb` panel:

* From `22:00` to `08:00`
* When the display is sleeping

System Preferences > Displays
-----------------------------

`Display` tab:

* Resolution: `Scaled`
* Larger Text

`Night Shift` tab:

* Schedule: `Sunset to Sunrise`
* Color Temperature: `3/4`

System Preferences > Energy Saver
---------------------------------

`Power Adapter` tab:

> To switch display off while computing:

* Prevent computer from sleeping automatically when the display is off

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

Note: to use functional keys in some applications, add them in
`Shortcuts` tab > `Function Keys` panel (see below).

`Text` tab:

* Spelling: `Set Up...`

`Shortcuts` tab > `Input Sources` panel:

* Select the previous input source: `^Space`

> For `MacBook Pro 15"`:

`Shortcuts` tab > `Function Keys` panel:

* Add: `Terminal`
* Add: `Visual Studio Code`
* Add: `Blender`
* Add: `/System/Library/Frameworks/Tk.framework/Versions/<VER>/Resources/Wish.app`
* Add: `/usr/local/Cellar/git/<VERSION>/share/git-gui/lib/Git Gui.app`

Note: press `Command + Shift + .` to show hidden files in the open file dialog.

> To use keyboard in dialogs:

* All controls

`Input Sources` tab:

* `U.S.`
* `Canadian French - CSA`
* `Ukrainian - PC`
* `Polish - Pro`
* `Russian - PC`

`Dictation` tab:

* Dictation: `On`

System Preferences > Trackpad
-----------------------------

`Point & Click` tab:

* Tap to click
* Tracking speed: `3/4`

System Preferences > Printers & Scanners
----------------------------------------

Setup printers.

System Preferences > Sound
--------------------------

* Show volume in menu bar

System Preferences > Internet accounts
--------------------------------------

Add email accounts.

System Preferences > Network
----------------------------

Select the correct network and:

* Automatically join this network

System Preferences > Sharing
----------------------------

* Computer Name

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

* Uncheck: Show fast user switching menu as

System Preferences > Siri
-------------------------

* Keyboard Shortcut: `Press Fn (Function) Space`
* Language: `Russian`
* Siri Voice: `Female`
* Voice Feedback: `Off`
* Uncheck: Show Siri in menu bar

> For `MacBook Pro 15"`:

* Listen for "Привет, Siri"
* Allow Siri when locked

System Preferences > Date & Time
--------------------------------

`Clock` tab:

* Date options: `Show date`

System Preferences > Time Machine
---------------------------------

* Show Time Machine in menu bar

`Options` dialog:

* Exclude these items: `~/nob` and `~/Downloads/nob`

System Preferences > Language & Region
--------------------------------------

At the very end, remove all the languages but `English (US)`

Desktop Preferences
-------------------

* Right Click > `Use Stacks`

Keep on Dock:

* `Calculator`
* `Instruments`
* `Terminal`

Remove from Dock:

* `Siri`
* `Pages`
* `Numbers`
* `Keynote`
* `Contacts`
* `System Preferences`
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

* New window open with: `Top Sites`
* New tabs open with: `Top Sites`
* Safari opens with: `All windows from last session`

`Advanced` tab:

For `Responsive Design Mode` (`Control + Command + R`):

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

App Store Applications
----------------------

* `XCode`

Homebrew Cask Applications
--------------------------

Homebrew installation (see <http://brew.sh>):

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

To install all Cask applications:

```bash
brew tap homebrew/cask-versions # For code-insiders
brew cask install firefox google-chrome adoptopenjdk meld minikube osxfuse virtualbox visual-studio-code-insiders wireshark xquartz blender gimp inkscape vlc viscosity
```

General Casks:

* Firefox (browser): `firefox`
* Google Chrome (browser): `google-chrome`

Casks for Development:

* OpenJDK (for Closure compiler): `adoptopenjdk`
* Git GUI Merge Tool: `meld`
* Minikube (local Kubernetes): `minikube`
* FUSE for macOS (for sshfs): `osxfuse`
* Oracle VirtualBox (virtual machine hypervisor): `virtualbox`
* Visual Studio Code IDE (vscode): `visual-studio-code-insiders`
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

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

To install all applications:

```bash
brew install aspell bash-completion gawk mc p7zip watch wget clang-format cloc closure-compiler cmake git htop kubernetes-cli kubernetes-helm python shfmt sshfs wireshark ffmpeg imagemagick az
```

General formulas:

* Spell Checker: `aspell`
* Programmable Completion for Bash: `bash-completion`
* GNU AWK: `gawk`
* Midnight Commander (File Manager): `mc`
* 7zip: `p7zip`
* Execute a Program Periodically: `watch`
* Network Downloader: `wget`

Formulas for Development:

* C/C++ Language Formatter: `clang-format`
* Count Lines of Code: `cloc`
* Google Javascript Compiler: `closure-compiler`
* CMake Build System: `cmake`
* Version Control System: `git`
* Interactive Process Viewer: `htop`
* Kubernetes kubectl Tool: `kubernetes-cli`
* Kubernetes Package Manager: `kubernetes-helm`
* Python Version 3: `python`
* Shell Language Formatter: `shfmt`
* SSH File System: `sshfs`
* Network Traffic Analyzer: `wireshark`

Graphics formulas:

* Video Convertor: `ffmpeg`
* Batch Image Manipulation: `imagemagick`

Cloud formulas:

* Azure CLI: `az`

> To fix the "invalid object doesn't have additional properties" error:

```bash
rm /usr/local/bin/kubectl
brew link --overwrite kubernetes-cli
```

Visual Studio Code (vscode)
---------------------------

To install VS Code:

```bash
brew tap homebrew/cask-versions
brew cask install visual-studio-code-insiders
```

Extensions to install:

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
}
```

Keyboard shortcuts:

```javascript
Tasks: Run Test Task Command + Shift + A
```

VS Code also requires few Homebrew applications to be installed:

```bash
brew install git clang-format python shfmt
```

To install `pylint`:

```bash
sudo easy_install pip
sudo pip install pylint
```

Terminal Preferences
--------------------

`Profiles` tab:

* Select Homebrew panel and click `Default`

`Text` tab:

* Font > Change... > Size: `18pt`

`Shell` tab:

* When the shell exits: `Close if the shell exited cleanly`

`Keyboard` tab:

* Use Option as Meta key
* Double click `F11` key to edit > Key: `F1` Modifier: `Shift`
* Repeat for `F12-F20` keys

Terminal Profiles
-----------------

File `~/.bashrc`:

```bash
# The sub-shell prompt
export PS1="\u@\h:\W \$ "

alias ll="ls -GFhla"
alias ls="ls -GFha"
alias mc="mc -d -S gotar"
alias mcedit="mcedit -d -S gotar"
alias top="top -o cpu" # optional for macOS

[[ -r "/usr/local/etc/profile.d/bash_completion.sh" ]] && . "/usr/local/etc/profile.d/bash_completion.sh"
```

File `~/.profile`:

```bash
. "${HOME}/.bashrc"

export PATH="${HOME}/bin:${PATH}"
export EDITOR="mcedit"
export BLOCKSIZE="1K"
export LC_ALL="en_US.UTF-8"

# The interactive prompt
export PS1="[\t] \u@\h:\w \$ "
```

Midnight Commander (mc) Preferences
-----------------------------------

Ubuntu: `Options > Configuration`:

* Use internal edit

`Options > Layout`:

* Uncheck: Menubar visible
* Uncheck: Hintbar visible

`Options > Appearance`:

* Skin: `gotar`

`Options > Confirmation...`:

* Uncheck: Confirmation|Exit

`Options > Display bits`:

* Input / display codepage: `UTF-8`

`Editor > Options > General`:

* Uncheck: Confirm before saving

git Preferences
---------------

```bash
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
   ```bash
   cat ~/.ssh/id_rsa.pub
   ```
* Paste the key into GitHub.

Mail Preferences
----------------

`Composing` tab:

* Message Format: `Plain Text`

Docker Installation and Preferences
-----------------------------------

Install Docker from <http://docker.com> or from Homebrew Cask.

Docker Preferences > Advanced

* Memory: `8GB`
* Swap: `4GB`

Symbolic Links Installation
---------------------------

```bash
cd && ln -s /usr/local .
cd && ln -s /usr/local/etc .
cd /usr/local/bin && ln -s code-insiders code
cd && ln -s Library/Fonts .
```

iTunes Preferences
------------------

`Devices` tab:

> To prevent iTunes auto start on iPhone connection:

* Prevent iPods, iPhones and iPads from syncing automatically

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
