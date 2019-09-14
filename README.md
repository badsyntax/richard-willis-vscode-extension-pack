# VSCode Extension Pack for Richard Willis

Search for "Richard Willis Extension Pack" in the extensions panel in vscode to install.

👉 [Create your own extension pack](https://code.visualstudio.com/blogs/2017/03/07/extension-pack-roundup)

## Extension Release Process

This extension is built and published to the extension marketplace with GitHub Actions.

To publish a new version, create a new GitHub Release, bumping the tag version. This tag version will be used for the extension version.

Refer to the [github workflow](./.github/workflows/nodejs.yml).

## Recommended Settings

You need to install the `Fira Code` font like so:

```bash
brew tap homebrew/cask-fonts
brew install font-fira-code
```

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
  "java.configuration.updateBuildConfiguration": "automatic",
  "breadcrumbs.enabled": true,
  "explorer.confirmDragAndDrop": false,
  "editor.fontFamily": "Fira Code, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": false,
  "editor.fontSize": 14,
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
  "jest.pathToJest": "npm test --",
  "jest.debugCodeLens.showWhenTestStateIn": [
    "fail",
    "unknown",
    "pass"
  ],
  "jest.autoEnable": false,
  "html.suggest.html5": true,
  "html.validate.scripts": true,
  "html.validate.styles": true,
  "stylelint.config": {
    "ignoreFiles": ["**/*.js", "**/*.jsx"]
  },
  "window.zoomLevel": 0,
  "[shellscript]": {
    "editor.defaultFormatter": "foxundermoon.shell-format"
  },
  "[dockerfile]": {
    "editor.defaultFormatter": "foxundermoon.shell-format"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[xml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[yaml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```

## License

See [LICENSE.md](./LICENSE.md).
