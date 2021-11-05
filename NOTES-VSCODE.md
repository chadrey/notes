Here lie notes taken from my latest transition to the [VS Code text editor](https://code.visualstudio.com/).

Don't forget about [the docs](https://code.visualstudio.com/docs) and [the release reviews](https://code.visualstudio.com/updates).


# VS Code Application
* **ctl-A ctl-S**  Keyboard shortcuts
* **ctl-shift-P**  command palette
* **ctl-shift-E**  Explorer
* **ctl-shift-F**  Search
* **ctl-shift-G**  Source Control
* **ctl-shift-D**  Run and Debug
* **ctl-shift-X**  Extensions
* **ctl-,**        Settings
* **ctl-`**        Toggle Terminal
* **ctl-E**        Goto File
* **ctl-F4**       Close selected window
* **** 

# Code Editing
* **alt-arrow**  Move line up (or down)
* **ctl-shift-alt-arrows** Column mode
* **ctl-/**      Toggle comments for selection
* **ctl-p**      Open search bar for file open (of files in your project)
* **tab**        Indent selection
* **shift-tab**  Unindent selection
* **ctl-n**      New file
* **f2**         Rename file
* **ctl-enter**  New line below
* **ctl-left/right arrow** Move cursor whole words at a time
* **ctl-l**      Select the whole line
* ****


## [Thanks Kyle and WebDevSimplified](https://blog.webdevsimplified.com/2020-08/10-best-keyboard-shortcuts/)
### Copy/Cut/Paste entire lines
With no selection, copy/cut/paste will work on the entire line.

# [Package: Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
* **ctl-alt-k** Toggle
* **ctl-alt-l** Move to next
* **ctl-alt-j** Move to previous
* **ctl-alt-c** Clear


# [Package: Insert Numbers](https://marketplace.visualstudio.com/items?itemName=Asuka.insertnumbers#:~:text=Insert%20Numbers%20for%20Visual%20Studio%20Code.%20An%20extension,two%20ways%20to%20change%20the%20default%20format%20string.)
* **ctl-alt-n**    Insert Numbers

* **%3d**          Insert with leading spaces (3 wide)
* **%03d**         Insert with leading zeros (3 wide)
* **%03X**         Insert (hex) with leading zeros
* **%03:0:4**      Insert starting at 0 and stepping by 4

*Uses sprintf type of formatting.  See [this link](https://github.com/alexei/sprintf.js) for more info.*

# [Python Indent](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent&ssr=true)
No keyboard shortcuts...

# [Python DocString Generator](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)
Cursor must be on the line directly below the definition to generate full auto-populated docstring.
Then press enter after opening docstring with triple quotes (""" or ''')

# Packages to consider
* [AREPL](https://marketplace.visualstudio.com/items?itemName=almenon.arepl#:~:text=AREPL%20automatically%20evaluates%20python%20code%20in%20real-time%20as,is%20availible%20for%20free%20on%20the%20vscode%20marketplace.)
* [Kite AutoComplete](https://marketplace.visualstudio.com/items?itemName=kiteco.kite)
  *  (Provides better completion and codehelp)
