# VS Code Settings

---

# Theme
[Dracula](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula&ssr=false#qna)

---

# Extensions

* [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
    * Highlight hex-code colors in Editor
* [Live Server](https://marketplace.visualstudio.com/items?itemName=yandeu.five-server)
    * Open any file in local server from Editor itself
* [Open in browser](https://marketplace.visualstudio.com/items?itemName=techer.open-in-browser)
    * Open any file directly from Editor in browser
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
    * Automatically completes file-path
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    * Format code (HTML, JS, CSS)
* [Atomic CSS Search](https://marketplace.visualstudio.com/items?itemName=ArvinH.atomic-css-search)
    * Easily find Atomic CSS classes
* [Filesize](https://marketplace.visualstudio.com/items?itemName=mkxml.vscode-filesize)
    * Displays the filesize at the status bar in Editor
---

# Settings

```
{
    "editor.wordWrap": "on",
    "editor.fontFamily": "Menlo, Monaco, 'Courier New', monospace",
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.linkedEditing": true,
    "editor.fontSize": 14,
    "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
    "window.title": "${activeEditorMedium}${separator}${rootName}",
    "workbench.colorTheme": "Dracula",
    "workbench.sideBar.location": "right",
    "terminal.external.osxExec": "iTerm.app",
    "terminal.explorerKind": "external",
    "search.useGlobalIgnoreFiles": true,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "html.format.templating": true,
    "html.format.indentInnerHtml": true,
    "diffEditor.renderSideBySide": false,
    "files.autoSave": "onFocusChange",
    "files.exclude": {
        "**/.DS_Store": true,
        "**/.hg": true,
        "**/.svn": true,
        "**/CVS": true,
        "wp-content/cache/**/*": true,
        "wp-includes/**/*": true
    },
    "prettier.printWidth": 120,
    "prettier.tabWidth": 4,
    "workbench.colorCustomizations": {
        "sideBar.background": "#000",
        "activityBar.background": "#111",
        "editor.background": "#000",
    },
}
```
