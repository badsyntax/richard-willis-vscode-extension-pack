# VSCode Extension Pack for Richard Willis

Search for "Richard Willis Extension Pack" in the extensions panel in vscode to install.

👉 [Create your own extension pack](https://code.visualstudio.com/blogs/2017/03/07/extension-pack-roundup)

## Extension Release Process

This extension is built and published to the extension marketplace with GitHub Actions.

To publish a new version, create a new GitHub Release, bumping the tag version. This tag version will be used for the extension version.

Refer to the [github workflow](./.github/workflows/nodejs.yml).

## Recommended Settings

```json
{
  "workbench.colorCustomizations": {
    "statusBar.background": "#000000",
    "statusBar.noFolderBackground": "#000000"
  },
  "workbench.startupEditor": "newUntitledFile",
  "workbench.settings.enableNaturalLanguageSearch": false,
  "telemetry.enableCrashReporter": false,
  "telemetry.enableTelemetry": false,
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "java.implementationsCodeLens.enabled": true,
  "java.referencesCodeLens.enabled": true,
  "java.configuration.checkProjectSettingsExclusions": false,
  "breadcrumbs.enabled": true,
  "editor.renderWhitespace": "all",
  "editor.suggestSelection": "first",
  "editor.formatOnSave": false,
  "editor.smoothScrolling": true,
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": true,
  "eslint.autoFixOnSave": true,
  "editor.tabSize": 2,
  "editor.insertSpaces": true,
  "editor.detectIndentation": true,
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "python.jediEnabled": false,
  "gitlens.codeLens.enabled": false,
  "go.enableCodeLens": {
    "references": false,
    "runtest": true
  },
  "html.suggest.html5": true,
  "html.validate.scripts": true,
  "html.validate.styles": true,
  "stylelint.config": {
    "ignoreFiles": ["**/*.js", "**/*.jsx"]
  },
  "[shellscript]": {
    "editor.defaultFormatter": "foxundermoon.shell-format",
    "editor.formatOnSave": true
  },
  "[dockerfile]": {
    "editor.defaultFormatter": "foxundermoon.shell-format",
    "editor.formatOnSave": true
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
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
  "[xml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[python]": {
    "editor.formatOnSave": true
  },
  "[yaml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  }
}
```

## License

See [LICENSE.md](./LICENSE.md).
