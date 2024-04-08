# VS Code Settings

## Extensions

* Theme / Editor Experience
  * [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
    * Change the font size with keyboard shortcuts.
  * [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
    * Nice / colorful icons for many different file types
  * [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
    * Integrates ESLint JS
  * [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    * Automatically format javascript, JSON, CSS, Sass
  * [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
    * Auto generate TypeScript (and other languages) types from JSON data., and HTML files.
  * [PostCSS Intellisense and Highlighting](https://marketplace.visualstudio.com/items?itemName=vunguyentuan.vscode-postcss)
    * Works better than the other more popular one of a similar name.
  * [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
    * Spell check markdown, comments and variable names.
  * [Pretty TypeScript Errors](https://marketplace.visualstudio.com/items?itemName=yoavbls.pretty-ts-errors)
    * Makes TS errors more human readable.
* Useful Tools
  * [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
    * Auto generate TypeScript (and other languages) types from JSON data.
  * [Code Snap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)
    * Take pictures of code with your VS Code Theme / Font settings.
  * [Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)
    * Make HTTP requests from inside VS Code (similar to Postman / Insomnia).
* Languages and Libraries
  * [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml)
    * XML Formatting, XQuery, and XPath Tools for Visual Studio Code.
  * [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
    * Intelligent Tailwind CSS tooling for VS Code.
  * React
    * [ES7+ React/Redux/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
      * Extensions for React, React-Native and Redux in JS/TS with ES7+ syntax. Customizable. Built-in integration with prettier.
    * [CSS in JS](https://marketplace.visualstudio.com/items?itemName=paulmolluzzo.convert-css-in-js)
      * Get syntax highlighting when working with CSS in JS template strings.
    * [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components)
      * Syntax highlighting for styled-components.
   * [htmx-tags](https://marketplace.visualstudio.com/items?itemName=otovo-oss.htmx-tags)
    * Provides HTMX tag completion in HTML files in VSCode
  * [Markdown Mermaid Preview](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)
    * View Mermaid diagrams when previewing Markdown.

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
