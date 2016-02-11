This document is a collection of custom keybindings for VSCode.


These keybindings are simplified controls for moving around working files.

Keybind Description:

    Pressing alt+cmd+down will go to the next working file.
    Pressing alt+cmd+up will go to the previous working file.

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
