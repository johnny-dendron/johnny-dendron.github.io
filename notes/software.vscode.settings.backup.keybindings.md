---
id: nylmhjgd6pebnftuir51nri
title: Keybindings
desc: ''
updated: 1656190049589
created: 1656189943697
---

    [
      {
        "key": "ctrl+r",
        "command": "-workbench.action.quickOpenNavigateNextInRecentFilesPicker",
        "when": "inQuickOpen && inRecentFilesPicker"
      },
      {
        "key": "ctrl+r",
        "command": "-workbench.action.openRecent"
      },
      {
        "key": "ctrl+\\",
        "command": "-workbench.action.splitEditor"
      },
      {
        "key": "ctrl+\\",
        "command": "workbench.action.toggleSidebarVisibility"
      },
      {
        "key": "ctrl+b",
        "command": "-workbench.action.toggleSidebarVisibility"
      },
      {
        "key": "ctrl+alt+\\",
        "command": "workbench.action.splitEditor"
      },
      {
        "key": "ctrl+shift+\\",
        "command": "-editor.action.jumpToBracket",
        "when": "editorTextFocus"
      },
      {
        "key": "ctrl+shift+\\",
        "command": "-workbench.action.terminal.focusTabs",
        "when": "terminalFocus && terminalHasBeenCreated || terminalFocus && terminalProcessSupported || terminalHasBeenCreated && terminalTabsFocus || terminalProcessSupported && terminalTabsFocus"
      },
      {
        "key": "ctrl+shift+\\",
        "command": "workbench.action.closeActiveEditor"
      },
      {
        "key": "ctrl+f4",
        "command": "-workbench.action.closeActiveEditor"
      },
      {
        "key": "ctrl+shift+alt+\\",
        "command": "workbench.action.splitEditorDown"
      },
      {
        "key": "ctrl+shift+alt+z",
        "command": "dendron.createScratchNote",
        "when": "dendron:pluginActive"
      },
      {
        "key": "ctrl+shift+s",
        "command": "-dendron.createScratchNote",
        "when": "dendron:pluginActive"
      },
      {
        "key": "ctrl+shift+alt+4",
        "command": "workbench.action.editorLayoutTwoByTwoGrid"
      },
      {
        "key": "ctrl+shift+alt+1",
        "command": "workbench.action.editorLayoutSingle"
      },
      {
        "key": "ctrl+shift+alt+3",
        "command": "workbench.action.editorLayoutThreeColumns"
      },
      {
        "key": "ctrl+shift+alt+2",
        "command": "workbench.action.editorLayoutTwoColumns"
      },
      {
        "key": "ctrl+shift+alt+`",
        "command": "workbench.action.toggleCenteredLayout"
      }
    ]
