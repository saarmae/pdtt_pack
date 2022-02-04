# README

**Optional**: If you want to remove one or more extensions that come with this pack:
1. Install this extension pack.
2. Uninstall this extension pack without removing the extensions.

After this you can remove single extensions you don't care about. While the pack is installed it won't allow separately uninstalling the extensions.

## Included extensions

[Node.js Extension Pack](https://github.com/waderyan/nodejs-extension-pack)<br/>
[Docker](https://github.com/microsoft/vscode-docker)<br/>
[EditorConfig for VS Code](https://github.com/editorconfig/editorconfig-vscode)<br/>
[File Utils](https://github.com/sleistner/vscode-fileutils)<br/>
[Gitignore](https://github.com/CodeZombieCH/vscode-gitignore)<br/>
[Git Blame](https://github.com/Sertion/vscode-gitblame)<br/>
[Prettier](https://github.com/prettier/prettier-vscode)<br/>
[Vscode-icons](https://github.com/vscode-icons/vscode-icons)<br/>
[Snyk Vulnerability Scanner](https://github.com/snyk/vscode-extension)<br/>
[Coverage Gutters](https://github.com/ryanluker/vscode-coverage-gutters)<br/>

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

```
{
    "editor.cursorBlinking": "phase",
    "editor.cursorStyle": "line",
    "editor.cursorWidth": 2,
    "editor.fontFamily": "Fira Code, Menlo, Monaco, 'Courier New', monospace",
    "editor.lineNumbers": "on",
    "editor.minimap.enabled": false,
    "editor.quickSuggestions": {
        "comments": true,
        "other": true,
        "strings": true
    },
    "editor.renderWhitespace": "none",
    "editor.rulers": [
        120
    ],
    "explorer.confirmDelete": false,
    "files.insertFinalNewline": true,
    "files.trimTrailingWhitespace": true,
    "npm-intellisense.importES6": false,
    "prettier.eslintIntegration": true,
    "prettier.printWidth": 120,
    "prettier.singleQuote": true,
    "prettier.tabWidth": 4,
    "prettier.trailingComma": "all",
    "prettier.useTabs": true,
    "terminal.external.osxExec": "iterm2.app",
    "terminal.integrated.cursorBlinking": true,
    "terminal.integrated.cursorStyle": "line",
    "terminal.integrated.fontFamily": "Inconsolata for powerline, Fira Code, Menlo, monospace",
    "vsicons.dontShowNewVersionMessage": true,
    "window.zoomLevel": 0,
    "workbench.colorTheme": "Cobalt2",
    "workbench.fontAliasing": "default",
    "workbench.iconTheme": "vscode-icons",
    "workbench.settings.editor": "json",
    "workbench.startupEditor": "welcomePage",
    "workbench.statusBar.feedback.visible": false,
    "telemetry.enableCrashReporter": false,
    "telemetry.enableTelemetry": false,
    "workbench.settings.useSplitJSON": true,
    "editor.guides.bracketPairs": true,
    "editor.bracketPairColorization.enabled": true
    // "editor.fontLigatures": true,
    // "files.autoSave": "afterDelay",
}
```
