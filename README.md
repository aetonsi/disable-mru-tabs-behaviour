# Disable MRU tabs behaviour README

Simple keybindings / keymap to disable the annoying MRU behaviour which is the default of the VS Code editor.

This is all this extension does:

```json
[
  {
    "key": "ctrl+tab",
    "command": "workbench.action.nextEditor"
  },
  {
    "key": "ctrl+shift+tab",
    "command": "workbench.action.previousEditor"
  }
]
```
