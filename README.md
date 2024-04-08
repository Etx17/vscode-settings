# VS Code Settings

### Extension package names for easy install

```
Jupyter
remote -ssh
vs code great icons
github copilot chat
beautify
dev containers
docker
es7 + React/redux/react native snippets
eslint
gitblame
git graph
gitlens
indent rainbow
mithril emmet
past and indent
prettier
ruby lsp
fontsize shortcust
thunder client

```

# Settings

```json
{
    "[python]":
    {
        "editor.bracketPairColorization.enabled": false,
        "editor.guides.bracketPairs": false,
        "editor.tabSize": 4
    },
    "editor.bracketPairColorization.enabled": true,
    "editor.detectIndentation": false,
    "editor.fontSize": 14,
    "editor.guides.bracketPairs": true,
    "editor.minimap.enabled": false,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.renderControlCharacters": true,
    "editor.linkedEditing": true,
    "editor.rulers":
    [
        80,
        120
    ],
    "editor.showFoldingControls": "always",
    "editor.snippetSuggestions": "top",
    "editor.tabSize": 2,
    "emmet.includeLanguages":
    {
        "erb": "html"
    },
    "emmet.showSuggestionsAsSnippets": true,
    "emmet.triggerExpansionOnTab": true,
    "explorer.confirmDelete": false,
    "files.exclude":
    {
        "**/.DS_Store": true,
        "**/.egg-info": true,
        "**/.git": true,
        ".asset-cache": true,
        ".bundle": true,
        ".ipynb_checkpoints": true,
        ".pytest_cache": true,
        ".sass-cache": true,
        ".svn": true,
        "__pycache__": true,
        "_site": true,
        "build": true,
        "coverage": true,
        "dist": true,
        "log": true,
        "node_modules": true,
        "public/packs": true,
        "tmp": true
    },
    "files.hotExit": "off",
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    "files.trimTrailingWhitespace": true,
    "files.watcherExclude":
    {
        "**/audits/**": true,
        "**/coverage/**": true,
        "**/log/**": true,
        "**/node_modules/**": true,
        "**/tmp/**": true,
        "**/vendor/**": true
    },
    "python.defaultInterpreterPath": "~/.pyenv/shims/python",
    "python.formatting.provider": "yapf",
    "python.terminal.activateEnvironment": false,
    "ruby.lint":
    {
        "rubocop": true
    },
    "telemetry.telemetryLevel": "off",
    "window.restoreWindows": "none",
    "workbench.settings.editor": "json",
    "workbench.settings.openDefaultSettings": true,
    "workbench.statusBar.visible": false,
    "workbench.settings.useSplitJSON": true,
    "workbench.sideBar.location": "right",
    "workbench.startupEditor": "newUntitledFile",
    "editor.accessibilitySupport": "off",
    "editor.inlineSuggest.enabled": true,
    "explorer.confirmDragAndDrop": false,
    "terminal.integrated.enableMultiLinePasteWarning": false,
    "workbench.iconTheme": "vscode-great-icons",
    "files.autoSave": "afterDelay",
    "window.commandCenter": true,
    "zenMode.hideStatusBar": false,
    "editor.lineHeight": 0
}

```

# Keybindings

```json
[
  {
    "key": "cmd+1",
    "command": "workbench.action.openEditorAtIndex1"
  },
  {
    "key": "ctrl+1",
    "command": "-workbench.action.openEditorAtIndex1"
  },
  {
    "key": "cmd+2",
    "command": "workbench.action.openEditorAtIndex2"
  },
  {
    "key": "ctrl+2",
    "command": "-workbench.action.openEditorAtIndex2"
  },
  {
    "key": "cmd+3",
    "command": "workbench.action.openEditorAtIndex3"
  },
  {
    "key": "ctrl+3",
    "command": "-workbench.action.openEditorAtIndex3"
  },
  {
    "key": "cmd+4",
    "command": "workbench.action.openEditorAtIndex4"
  },
  {
    "key": "ctrl+4",
    "command": "-workbench.action.openEditorAtIndex4"
  },
  {
    "key": "cmd+5",
    "command": "workbench.action.openEditorAtIndex5"
  },
  {
    "key": "ctrl+5",
    "command": "-workbench.action.openEditorAtIndex5"
  },
  {
    "key": "cmd+6",
    "command": "workbench.action.openEditorAtIndex6"
  },
  {
    "key": "ctrl+6",
    "command": "-workbench.action.openEditorAtIndex6"
  },
  {
    "key": "cmd+7",
    "command": "workbench.action.openEditorAtIndex7"
  },
  {
    "key": "ctrl+7",
    "command": "-workbench.action.openEditorAtIndex7"
  },
  {
    "key": "cmd+8",
    "command": "workbench.action.openEditorAtIndex8"
  },
  {
    "key": "ctrl+8",
    "command": "-workbench.action.openEditorAtIndex8"
  },
  {
    "key": "cmd+9",
    "command": "workbench.action.openEditorAtIndex9"
  },
  {
    "key": "ctrl+9",
    "command": "-workbench.action.openEditorAtIndex9"
  },
  {
    "key": "ctrl+1",
    "command": "workbench.action.focusFirstEditorGroup"
  },
  {
    "key": "cmd+1",
    "command": "-workbench.action.focusFirstEditorGroup"
  },
  {
    "key": "ctrl+3",
    "command": "workbench.action.focusThirdEditorGroup"
  },
  {
    "key": "cmd+3",
    "command": "-workbench.action.focusThirdEditorGroup"
  },
  {
    "key": "ctrl+6",
    "command": "workbench.action.focusSixthEditorGroup"
  },
  {
    "key": "cmd+6",
    "command": "-workbench.action.focusSixthEditorGroup"
  },
  {
    "key": "ctrl+7",
    "command": "workbench.action.focusSeventhEditorGroup"
  },
  {
    "key": "cmd+7",
    "command": "-workbench.action.focusSeventhEditorGroup"
  },
  {
    "key": "ctrl+2",
    "command": "workbench.action.focusSecondEditorGroup"
  },
  {
    "key": "cmd+2",
    "command": "-workbench.action.focusSecondEditorGroup"
  },
  {
    "key": "ctrl+4",
    "command": "workbench.action.focusFourthEditorGroup"
  },
  {
    "key": "cmd+4",
    "command": "-workbench.action.focusFourthEditorGroup"
  },
  {
    "key": "ctrl+5",
    "command": "workbench.action.focusFifthEditorGroup"
  },
  {
    "key": "cmd+5",
    "command": "-workbench.action.focusFifthEditorGroup"
  },
  {
    "key": "ctrl+8",
    "command": "workbench.action.focusEighthEditorGroup"
  },
  {
    "key": "cmd+8",
    "command": "-workbench.action.focusEighthEditorGroup"
  }
]
```

## Past Themes

* Original theme I use in some videos:
  * [Seti-Monokai](https://marketplace.visualstudio.com/items?itemName=SmukkeKim.theme-setimonokai)
* I used this darker modification of the above theme for a few videos:
  * [Seti-Black](https://marketplace.visualstudio.com/items?itemName=bobsparadox.seti-black)
