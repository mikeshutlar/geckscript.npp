# GECKScript.npp

Enables Notepad++'s syntax highlighting and code completion for GECK Script, the scripting language used by Bethesda Softworks' Fallout 3 and Fallout: New Vegas.


## Features

* Colour scheme that's easy on the eyes
* Highlighting and completion for all built-in commands and syntax
* Includes all [Fallout Script Extender](http://fose.silverlock.org/) (FOSE) commands
* Includes all known [New Vegas Script Extender](http://nvse.silverlock.org/) (NVSE) commands as of NVSE v2 beta 9
* Associates .gek files with GECK Script when opened in Notepad++


## Install

Place the "plugins" folder into your Notepad++ program directory (e.g. C:\Program Files (x86)\Notepad++) & merge with the existing plugins folder.

Then open Notepad++, select `View -> User-Defined Dialogue...`, and click the `Import...` button. Navigate to and select the geckscript-lang.xml file, then close the dialog.


## Usage

Start saving your GECK scripts with the .gek file extension (e.g. mygroovyscript.gek), and Notepad++ will automatically recognise them and start highlighting. You can also select `Language -> GECKScript` in any file.

Press Ctrl+Space for code-completion.

To change the colours/fonts, go to `View -> User-Defined Dialogue...`, and select GECKScript in the User language dropdown box.


## Contribute

Something incorrect or missing, or got an improvement?

* Raise an [issue](https://github.com/infectedsoundsystem/geckscript.npp/issues)
* Or fork the repository, edit the file(s), and send a pull request


## Thanks

reinhart\_menken and Useruser3 - I previously used their highlighting and completion files for Notepad++, before creating my own. 

[Henning Hasemann](http://www.leetless.de/vim.html) - I roughly based the colour scheme on Vim's Pyte colorscheme


## GECKScript.vim

If you feel like upgrading to a hardcore text editor, check out [GECK Script syntax highlighting and autocompletion for Vim](https://github.com/infectedsoundsystem/geckscript.vim).


## License

Copyright (c) 2011, Mike Shutlar

Permission is granted to Do What The F\*\*\* You Want To these XML files under the terms of the [WTF Public License, Version 2](http://sam.zoy.org/wtfpl/)
