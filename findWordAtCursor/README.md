# [Find Word At Cursor](https://marketplace.visualstudio.com/items?itemName=mksafi.find-word-at-cursor)

This extension lets you quickly find the next word in the document that matches the current word under your cursor. It also works with a highlighted selection.

This extension provides the same functionality as IntelliJ's [Find Word At Caret](https://www.jetbrains.com/help/idea/finding-word-at-caret.html).

|Find word at cursor|Find selection|
|---|---|
|![](https://raw.githubusercontent.com/msafi/xvsc/master/findWordAtCursor/demoFiles/wordDemo.gif)|![](https://raw.githubusercontent.com/msafi/xvsc/master/findWordAtCursor/demoFiles/selectionDemo.gif)|

## Extension Settings

This extension adds two new commands:

* `findWordAtCursor.next`: moves the caret to the next word or selection under it
* `findWordAtCursor.previous`: moves the caret to previous word or selection under it

**Note** No keybinding is provided by this extension. You have to create one yourself.

On my Mac system, I've mapped these two commands to:

* `cmd+ctrl+down` for `findWordAtCursor.next`
* `cmd+ctrl+up` for `findWordAtCursor.previous`

## Checkout my other VS Code projects

They're listed and described [here](https://github.com/msafi/xvsc#projects-in-this-repo).

## To discuss stuff

Tweet at [@msafi](https://twitter.com/msafi)

## Issues, questions, etc

https://github.com/msafi/xvsc/issues
