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

System Preferences > Mission Control
------------------------------------

> To switch display off while computing:

* Hot Corners > bottom-right: `Put Display to Sleep`

System Preferences > Security & Privacy
---------------------------------------

`General` tab:

> To quickly switch display back on without a password:

* Require password `5 seconds` after sleep or screen saver begins

System Preferences > Notifications
----------------------------------

Do Not Disturb panel:

* From `22:00` to `08:00`
* When display is sleeping

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

`Text` tab:

* Spelling: `Set Up...`

`Shortcuts` tab > Input Sources panel:

* Select next source in Input menu

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

* Language: `Russian`
* Siri Voice: `Female`
* Voice Feedback: `Off`
* Uncheck: Show Siri in menu bar

System Preferences > Date & Time
--------------------------------

`Clock` tab:

* Date options: `Show date`

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

The option will persist across the Safari reloads.

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
brew cask install firefox google-chrome osxfuse visual-studio-code-insiders vmware-fusion xquartz blender gimp inkscape
```

General Casks:

* Firefox (browser): `firefox`
* Google Chrome (browser): `google-chrome`

Casks for Development:

* FUSE for macOS (for sshfs): `osxfuse`
* Visual Studio Code IDE (vscode): `visual-studio-code-insiders`
* VMWare Fusion (virtual machine hypervisor): `vmware-fusion`
* XQuartz (X11 Server): `xquartz`

Graphics Casks:

* Blender (3D graphics): `blender`
* GIMP (raster graphics): `gimp`
* Inkscape (vector graphics): `inkscape`

Homebrew Applications
---------------------

Homebrew installation (see <http://brew.sh>):

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

To install all applications:

```bash
brew install gawk mc wget clang-format closure-compiler cmake git htop python shfmt sshfs imagemagick
```

General formulas:

* GNU AWK: `gawk`
* Midnight Commander (file manager): `mc`
* GNU Wget File retrieving: `wget`

Formulas for Development:

* C/C++ Language Formatter: `clang-format`
* Google Javascript Compilator: `closure-compiler`
* CMake Build System: `cmake`
* Git version control system: `git`
* Interactive Process Viewer: `htop`
* Python version 3: `python`
* Shell Language Formatter: `shfmt`
* SSH file system: `sshfs`

Graphics formulas:

* Batch image manipulation: `imagemagick`

Visual Studio Code (vscode)
---------------------------

To install VS Code:

```bash
brew cask install visual-studio-code-insiders
```

Extensions to install:

* `C/C++`
* `Code Spell Checker`
* `CodeLLDB`
* `Markdown All in One`
* `Markdownlint`
* `Python`
* `shell-format`

Settings:

```javascript
{
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 100,
    "editor.dragAndDrop": false,
    "editor.rulers": [72, 80],
    "editor.fontSize": 16,
    "editor.renderWhitespace": "boundary",
    "editor.tabSize": 4,
    "C_Cpp.clang_format_style": "Google",
    "python.pythonPath": "python3",
}
```

VS Code also requires few Homebrew applications to be installed:

```bash
brew install git clang-format python shfmt
```

To install `pylint`:

```bash
pip install pylint
```

Terminal Preferences
--------------------

`Profiles` tab:

* Select Homebrew panel and click `Default`

`Text` tab:

* Font > Change... > Size: `18pt`

`Shell` tab:

* (optional) Run command: `mc`
* When the shell exits: `Close if the shell exited cleanly`

`Keyboard` tab:

* Use Option as Meta key
* Double click `F11` key to edit > Key: `F1` Modifier: `Shift`
* Repeat for `F12-F20` keys

Terminal Profiles
-----------------

.bashrc:
```bash
export PS1="[\t] \u@\h:\w \$ "

alias ll="ls -GFhla"
alias ls="ls -GFha"
alias mc="mc -d -S gotar"
alias mcedit="mcedit -d -S gotar"
alias top="top -o cpu" # optional for macOS
```

.profile:
```bash
. "${HOME}/.bashrc"

export PATH="${HOME}/bin:${PATH}"
export EDITOR="mcedit"
export BLOCKSIZE="1K"
export LC_ALL="en_US.UTF-8"

export PS1="[\t] \u@\h:\w \$ "
export PS2="\u@\h:\W \$ "
```

Midnight Commander (mc) Preferences
-----------------------------------

Ubuntu: Options > Configuration:

* Use internal edit

Options > Layout:

* Uncheck: Menubar visible
* Uncheck: Hintbar visible

Options > Appearance:

* Skin: `gotar`

Options > Confirmation...:

* Uncheck: Confirmation|Exit

Options > Display bits:

* Input / display codepage: `UTF-8`

Editor > Options > General

* Uncheck: Confirm before saving

SSH Preferences
---------------

* Run: `ssh-keygen -C email`
* To use for some hosts different user name add to `.ssh/config` the following:

```ssh
Host host.com
    User name
```

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

* `cd && ln -s /usr/local .`
* `cd && ln -s /usr/local/etc .`
* `cd /usr/local/bin && ln -s code-insiders code`
* `cd && ln -s Library/Fonts .`

Tools Installation
------------------

* TODO: `brew install https://raw.githubusercontent.com/kadwanev/bigboybrew/master/Library/Formula/sshpass.rb`
* TODO: tools repo: copy try, passwordless to ~/bin

iTunes Preferences
------------------

`Devices` tab:

> To prevent iTunes auto start on iPhone connection:

* Prevent iPods, iPhones and iPads from syncing automatically
