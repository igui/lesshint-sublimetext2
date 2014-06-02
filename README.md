#Less Syntax Check for Sublime Text

Based in [uipoet] [sublime-jshint](https://github.com/uipoet/sublime-jshint) project.

![ScreenShot](https://raw.github.com/uipoet/sublime-jshint/preview/jshint.png)

**Prerequisites:** [lessc](http://lesscss.org/#using-less-installation) and [Sublime Package Control](http://wbond.net/sublime_packages/package_control/installation)

**Mac OS X:** Installing node with homebrew or macports is assumed. The path to lessc is hardcoded in this plugin as `/usr/local/share/npm/bin:/usr/local/bin:/opt/local/bin`. There is no reliable way to get the path from your environment.

**Linux:** Make sure lessc is in your environment path.

**Windows:** Installing node with the Windows Installer from nodejs.org is assumed.

##1. Terminal

    npm install -g less
    
##2. Sublime Text Package Control

- Copy a the content of the repo to your packages Directory
- Restart Sublime Text

##3. JSHint an active JavaScript file

- `control`-`l` *or* `alt`-`l` in Linux/Windows *or* Tools/Contextual menus *or* the Command Palette


