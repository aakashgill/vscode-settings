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
  "editor.fontSize": 17,
  "window.zoomLevel": 0,
  "editor.wordWrap": "on",
  "files.autoSave": "onFocusChange",
  "workbench.editor.enablePreviewFromQuickOpen": false,
  "editor.fontFamily": "Monaco",
  "workbench.startupEditor": "newUntitledFile",
  "editor.multiCursorModifier": "ctrlCmd",
  "emmet.includeLanguages": {"javascript":"javascriptreact"},
  "terminal.external.osxExec": "iTerm.app",
  "terminal.explorerKind": "external",
  "workbench.statusBar.visible": true,
  "window.title": "${activeEditorMedium}${separator}${rootName}",
  "workbench.sideBar.location": "left",
  "gitlens.advanced.messages": {
      "suppressShowKeyBindingsNotice": true
  },
  "workbench.colorTheme": "Dracula",
  "editor.parameterHints": false
}

```
