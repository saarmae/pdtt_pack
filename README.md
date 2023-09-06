# README

**Optional**: If you want to remove one or more extensions that come with this pack:
1. Install this extension pack.
2. Uninstall this extension pack without removing the extensions.

After this you can remove single extensions you don't care about. While the pack is installed it won't allow separately uninstalling the extensions.

## Included extensions

[NPM Intellisense](https://github.com/ChristianKohler/NpmIntellisense)  
[Path Intellisense](https://github.com/ChristianKohler/PathIntellisense)  
[EditorConfig for VS Code](https://github.com/editorconfig/editorconfig-vscode)  
[markdownlint](https://github.com/DavidAnson/vscode-markdownlint)  
[ESLint](https://github.com/Microsoft/vscode-eslint)  
[Prettier](https://github.com/prettier/prettier-vscode)  
[Jest Runner](https://github.com/firsttris/vscode-jest-runner)  
[Shell Format](https://github.com/foxundermoon/vs-shell-format)  
[Pretty Typescript Errors](https://github.com/yoavbls/pretty-ts-errors)  

## Recommended font

[Fira Code](https://github.com/tonsky/FiraCode)

## Recommended font for integrated terminal

[Inconsolata for Powerline](https://github.com/powerline/fonts/tree/master/Inconsolata)

## Recommended theme

[Cobalt2](https://github.com/wesbos/cobalt2-vscode)

## Recommended settings

1. Open settings with `CMD + ,`
2. Search for `settings`
3. Change the `[Workbench › Settings: Editor]` value to from `UI` to `JSON`
3. Change the `[Workbench › Settings: Use Split JSON]` value to true
4. Save with `CMD + S`
5. Close and reopen settings again with `CMD + ,`
6. Change and replace the text in the right side with the settings below.
7. Save with `CMD + S`

Some controversial settings have been commented out, feel free to uncomment or delete.

```json
{
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "DavidAnson.vscode-markdownlint"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[shellscript]": {
    "editor.defaultFormatter": "foxundermoon.shell-format"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.bracketPairColorization.enabled": true,
  "editor.codeActionsOnSave": {
    "source.addMissingImports": true,
    "source.fixAll.eslint": true,
    "source.organizeImports": true
  },
  "editor.cursorBlinking": "phase",
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 2,
  "editor.fontFamily": "Fira Code, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.guides.bracketPairs": true,
  "editor.lineNumbers": "on",
  "editor.quickSuggestions": {
    "comments": "inline",
    "other": "inline",
    "strings": "inline"
  },
  "editor.renderWhitespace": "none",
  "editor.rulers": [120, 160],
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "files.autoSave": "off",
  "git.openDiffOnClick": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "jestrunner.runOptions": ["--testTimeout=100000000"],
  "telemetry.telemetryLevel": "off",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.fontFamily": "Inconsolata for powerline, Fira Code, Menlo, monospace",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "window.zoomLevel": 0,
  "workbench.colorTheme": "Cobalt2",
  "workbench.editor.enablePreview": false,
  "workbench.iconTheme": "icons",
  "workbench.settings.editor": "json",
  "workbench.settings.useSplitJSON": true,
  "workbench.sideBar.location": "right",
  "workbench.startupEditor": "welcomePage"
}
```
