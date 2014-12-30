# Setting Up Sublime Text 3

<p align="center"><img src="http://upload.wikimedia.org/wikipedia/en/4/4c/Sublime_Text_Logo.png" alt="Sublime Text Logo" width="120" ></p>

This is not a step by step guide for anyone who starts with [Sublime Text](http://www.sublimetext.com/), these are the settings and reminders that fit in my workflow. You can choose what to install.

> If they are useful to me, may also be useful for you.

## Sublime Text

Download and install [Sublime Text](http://www.sublimetext.com/).

[http://www.sublimetext.com/3](http://www.sublimetext.com/3)

## Packages

Packages in Sublime Text are a collection of resource files used to extend functionalities, they can be: plugins, syntax highlighting, menus, snippets...

There are a lot of custom packages to install, you can install packages to your necessity or you can create you own package.

### [Package Control](https://sublime.wbond.net/)

Package Control manage all packages, makes it simple to find, install, remove and keep packages up-to-date. 

#### To install

* Open Console in the menu options `View > Show Console`

* Paste the following code and execute

<code>import urllib.request,os,hashlib; h = '2deb499853c4371624f5a07e27c334aa' + 'bf8c4e67d14fb0525ba4f89698a6d7e1'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)</code>

#### How to use

Installing packages

* ctrl + shift + p
* Type `install`
* Select `Package Control: Install Package`
* Search the package you want to install

Removing packages

* ctrl + shift + p
* Type `remove`
* Select `Package Control: Remove Package`
* Find the package you want to remove


### [SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements)

Provides enhancements to the operations on Sidebar of Files and Folders for Sublime Text.

![screenshot sidebarEnhancements](http://dl.dropbox.com/u/43596449/tito/sublime/SideBar/screenshot.png)


<!--
### [AutoFileName](https://github.com/BoundInCode/AutoFileName)

### [AngularJS](https://github.com/angular-ui/AngularJS-sublime-package)

### [Bracket Highlighter](https://github.com/facelessuser/BracketHighlighter)

### [Can I Use](https://github.com/Azd325/sublime-text-caniuse)

Keyboard shortcut `ctrl+alt+f`

### [Color Picker](http://weslly.github.io/ColorPicker/)

Keyboard shortcut `ctrl+shift+c`

### [ColorHighlighter](https://github.com/Monnoroch/ColorHighlighter)

Disable keybindings

`tools -> color highlighter -> Disable default keybindings`

### [EditorConfig](http://editorconfig.org/)

### [Emmet](http://docs.emmet.io/)

### [GhostText](https://github.com/Cacodaimon/GhostText-for-SublimeText)

- [Extension for Chrome](https://chrome.google.com/webstore/detail/ghosttext-for-chrome/godiecgffnchndlihlpaajjcplehddca?utm_source=chrome-ntp-icon)

### [Gist](https://github.com/condemil/Gist)

### [Gulp](https://github.com/NicoSantangelo/sublime-gulp)

### [Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview)

### [SFTP](http://wbond.net/sublime_packages/sftp)

### [Tag](https://github.com/SublimeText/Tag)

### [Terminal](https://github.com/wbond/sublime_terminal)

Keyboard shortcut `ctrl+alt+shift+t` to project folder

Keyboard shortcut `ctrl+shift+t` to file

### [Trailing Spaces](https://github.com/SublimeText/TrailingSpaces)

### [Jquery](https://github.com/SublimeText/jQuery)


## Additional Syntax Support

### [Apache Conf](https://github.com/colinta/ApacheConf.tmLanguage)

### [LESS](https://github.com/danro/LESS-sublime)

### [Robots](https://github.com/andriyko/sublime-robot-framework-assistant)

### [SASS](https://sublime.wbond.net/packages/Sass)

### [Stylus](https://github.com/billymoon/Stylus)

- [Stylus-Snippets](https://github.com/billymoon/Stylus-Snippets)

### [Laravel Blade](https://github.com/Medalink/laravel-blade)


## Snippets

Local Folder

* Windows

`C:\Users\Name User\AppData\Roaming\Sublime Text 3\Packages\User`

[Comment Snippets](https://github.com/hachesilva/Comment-Snippets)

[JavaScript Console snippets](https://github.com/caiogondim/js-console-sublime-snippets)

[Jquery](https://sublime.wbond.net/packages/jQuery)

[Readme](https://gist.github.com/zenorocha/4526327) - Snippet from Zeno Rocha


## Key Bindings

### Mac OS

Super + b = `<strong>selection</strong>`

Super + i = `<em>selection</em>`

Super + u = `<u>selection</u>`

Super + alt + 7 = `encode_html_entities`

### Windows

Ctrl + b = `<strong>selection</strong>`

Ctrl + i = `<em>selection</em>`

Ctrl + u = `<u>selection</u>`

Ctrl + alt + 7 = `encode_html_entities`

## Tips

### Multiple Selection

`Ctrl+D` on Windows and Linux, or `Command+D` on OS X Quick Add Next

* `Alt+F3` on Windows and Linux, or `Ctrl+Command+G` on OS X. Find All

`Ctrl+Shift+L` or `Command+Shift+L` on OS X. Splitting the Selection into Lines

`Ctrl+K,Ctrl+D` on Windows and Linux, or `Command+K,Command+D` on OS X. Quick Skip Next

 if you go too far, use Undo Selection (Ctrl+U, or Command+U on OS X) to step backwards


* `Ctrl + k + Ctrl + v` = Paste History

* `f11` = full screen

* `shift + f11` = distract mode

### Workspace

* Layout in 2 columns `view/layout/Columns:2` or `alt+shift+2`

http://code.tutsplus.com/courses/perfect-workflow-in-sublime-text-2/lessons/your-first-snippet

https://realpython.com/blog/python/setting-up-sublime-text-3-for-full-stack-python-development/
https://github.com/mrmartineau/Placeholders
https://github.com/wbond/sublime_alignment
http://csscomb.com/
https://github.com/hachesilva/Comment-Snippets
https://github.com/caiogondim/js-console-sublime-snippets
http://www.sitepoint.com/10-essential-sublime-text-plugins-full-stack-developer/
 -->