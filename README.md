# SublimeText-PackageControl

This is the file to add package control to your [Sublime Text](https://www.sublimetext.com/).

## Installation

First, download this repository. 

Next, open `C:\Users\YOUR USER NAME\AppData\Roaming\Sublime Text 3\Installed Packages` and put the file `Package Control.sublime-package` in it.

Then, restart Sublime Text, open `Preferences → Package Settings → Package Control → Settings - User` in your Sublime and add this after `"bootstrapped": true,` :
```json
"channels":
[
    "https://rpdreamer.github.io/SublimeText-PackageControl/channel_v3.json"
],
```

Finally, restart Sublime Text, then you can use package control!

## Usage

Press `Ctrl + Shift + P` , then type `pci` and click `Package Control: Install Package`, type in the name of the package you want to install and click it. `[ = ]` will appear, when it disappears, the package has been installed already.

**Attention: The source code of Theme Boxy has been removed from github, so it cannot be installed!**