# Sublime TEXT:

## Must have packages:

* Package control =>  To install Package Control on ST3, open up the ST3′s console (View => Show Console or CTRL-`) and paste in the following:

```
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
```

* Sidebar Enchansment - improves the usability of the sidebar by giving you more options on new files, moving files, copying files and opening files in another program
* Advanced New Files - lets you create new file fast and easy with keys cmd/alt + N
* Bracket Highlighter - will highlight brackets surrounding the curso
* Git - The Git package lets you run Git commands
* GitGutter - GitGutter shows uncommitted additions, changes, and deletions
* Sublime Linter - Swiss knife of code linting, it highlights potential errors in your code depending on the language you are using

## For Pythonists:
* AutoPep8 - makes sure your code is in harmony with pep8 principles
* PythonFlake8 Lint - check Python files against some of the style conventions in PEP8, PyFlakes and mccabe.

## For Front-End-Developers:
* Emmet - Emmet makes coding HTML much easier by using shortcuts based on CSS selectors.
* SASS - adds SASS syntax and snippet support to Sublime Text
* LiveReload - automatically reloads the browser when the file is saved
* Prefixr - runs your CSS through the Prefixr API to make it Cross-Browser


# Sublime Text HotKeys

Essential key combinations:

* f11 - Toggle Full Screen
* shift + f11 - Toggle Distraction Free

* ctrl + space - Auto complete the current selected snippet
* ctrl + d Select the next occurrence of the selected word
* ctrl + k + b - Toggle the sidebar
* ctrl + / - Toggle a comment
* ctrl + l - select the entire current line
* ctrl + [ - Decreasing the indent
* ctrl + ] - increase the current line’s indent
* ctrl + shift + up/down - Swap with the line above\below
* ctrl + mouseclick - selects all the places you want to have a cursor
* ctrl + shift + / - Toggle a comment block
* ctrl + shift + d - Duplicate a line
* ctrl + shift + j - select all code that shares immediate indentation
* ctrl + shift + a -  select everything inside the current HTML tag
* ctrl + shift + v -  pasting with indentation

* alt + . - Close Tag
* ctrl + p - Show the go to overlay panel
* ctrl + shift + p - Show the command overlay panel
* ctrl + alt + p - Show the project selector panel
* ctrl + r - Show the go to overlay panel default to method selector
* ctrl + g - Show the go to overlay panel default to go to line selector
* ctrl + ; - Show the go to overlay panel default to variable selector
* ctrl + ` - Display console panel
* ctrl + k, ctrl + u - Toggle upper case
* ctrl + k, ctrl + l - Toggle lower case
