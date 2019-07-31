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
    "files.trimTrailingWhitespace": true,
    "files.insertFinalNewline": true,
    "editor.renderWhitespace": "all",
    "java.implementationsCodeLens.enabled": true,
    "java.referencesCodeLens.enabled": true,
    "java.configuration.checkProjectSettingsExclusions": false,
    "breadcrumbs.enabled": true,
    "editor.formatOnSave": false,
    "[css]": {
        "editor.formatOnSave": true
    },
    "eslint.autoFixOnSave": true,
    "[json]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[dockerfile]": {
        "editor.defaultFormatter": "foxundermoon.shell-format"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue"
}
```
