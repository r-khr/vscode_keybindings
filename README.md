This document is a collection of custom keybindings for VSCode.


These keybindings are simplified controls for moving around working files.

Keybind Description:

    Pressing _alt+cmd+down_ will go to the __next working file__.
    Pressing _alt+cmd+up_ will go to the __previous working file__.

Settings file:

    {
        "key": "alt+cmd+down",
        "command": "workbench.files.action.openNextWorkingFile",
        "when": "editorFocus"
    },{
        "key": "alt+cmd+up",
        "command": "workbench.files.action.openPreviousWorkingFile",
        "when": "editorFocus"
    }
