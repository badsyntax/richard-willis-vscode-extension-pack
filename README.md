# VSCode extension pack for Richard Willis

You can use it too.

Create your own extension pack: https://code.visualstudio.com/blogs/2017/03/07/extension-pack-roundup

## Settings

```json
{
  "workbench.colorCustomizations": {
    "statusBar.background": "#000000",
    "statusBar.noFolderBackground": "#000000"
  },
  "workbench.startupEditor": "newUntitledFile",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "java.implementationsCodeLens.enabled": true,
  "java.referencesCodeLens.enabled": true,
  "java.configuration.checkProjectSettingsExclusions": false,
  "breadcrumbs.enabled": true,
  "editor.renderWhitespace": "all",
  "editor.suggestSelection": "first",
  "editor.formatOnSave": false,
  "eslint.autoFixOnSave": true,
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "python.jediEnabled": false,
  "gitlens.codeLens.enabled": false,
  "go.enableCodeLens": {
    "references": false,
    "runtest": true
  },
  "[css]": {
    "editor.formatOnSave": true
  },
  "[shellscript]": {
    "editor.defaultFormatter": "foxundermoon.shell-format",
    "editor.formatOnSave": true
  },
  "[dockerfile]": {
    "editor.defaultFormatter": "foxundermoon.shell-format",
    "editor.formatOnSave": true
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": false
  }
}
```
