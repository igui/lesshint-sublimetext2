#Less Syntax Check for Sublime Text

Based in [uipoet's](https://github.com/uipoet/) [sublime-jshint](https://github.com/uipoet/sublime-jshint) project.

![ScreenShot](http://i59.tinypic.com/5f5kdy.jpg)

**Prerequisites:** [lessc](http://lesscss.org/#using-less-installation)

**Mac OS X:** Installing node with [homebrew](http://brew.sh/) or [macports](http://www.macports.org/) is assumed. The path to lessc is hardcoded in this plugin as `/usr/local/share/npm/bin:/usr/local/bin:/opt/local/bin` because there is no reliable way to get the path from your environment.

**Linux:** Make sure lessc is in your environment path.

**Windows:** Installing node with the [Windows Installer](http://nodejs.org/download/) from [nodejs.org](http://nodejs.org/) is assumed.

###1. Install Less Compiler

In general you can install [lessc](http://lesscss.org/#using-less-installation) using [npm](https://www.npmjs.org/).

    npm install -g lessc
    
###2. Sublime Text Package Control

1. Copy a the content of the repo to your packages Directory (e.g. `/home/user/.config/sublime-text-2/Packages/LessHint/`
)
2. Restart Sublime Text

###3. Less Syntax Check an active Less file

1. Save the file 
2. `control`-`l` *or* `alt`-`l` in Linux/Windows *or* Tools/Contextual menus *or* the Command Palette


