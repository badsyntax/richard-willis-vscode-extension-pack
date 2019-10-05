# VSCode Extension Pack for Richard Willis

Search for "Richard Willis Extension Pack" in the extensions panel in vscode to install.

👉 [Create your own extension pack](https://code.visualstudio.com/blogs/2017/03/07/extension-pack-roundup)

## Recommended Settings

You need to install the `Fira Code` font like so:

```bash
brew tap homebrew/cask-fonts
brew install font-fira-code
```

<details><summary>VS Code Settings</summary>

```json
{
  "workbench.colorCustomizations": {
    "statusBar.background": "#000000",
    "statusBar.noFolderBackground": "#000000"
  },
  "window.zoomLevel": 1,
  "workbench.startupEditor": "newUntitledFile",
  "workbench.settings.enableNaturalLanguageSearch": false,
  "telemetry.enableCrashReporter": false,
  "telemetry.enableTelemetry": false,
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "terminal.external.osxExec": "iTerm.app",
  "java.implementationsCodeLens.enabled": true,
  "java.referencesCodeLens.enabled": true,
  "java.configuration.checkProjectSettingsExclusions": false,
  "java.configuration.updateBuildConfiguration": "automatic",
  "breadcrumbs.enabled": true,
  "explorer.confirmDragAndDrop": false,
  "editor.fontFamily": "Fira Code, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": false,
  "editor.fontSize": 13,
  "editor.renderWhitespace": "all",
  "editor.suggestSelection": "first",
  "editor.formatOnSave": false,
  "editor.smoothScrolling": true,
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": true,
  "editor.tabSize": 2,
  "editor.insertSpaces": true,
  "editor.detectIndentation": true,
  "eslint.autoFixOnSave": true,
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
  },
  "cSpell.enabledLanguageIds": [
    "asciidoc",
    "c",
    "cpp",
    "csharp",
    "css",
    "git-commit",
    "go",
    "handlebars",
    "haskell",
    "html",
    "jade",
    "java",
    "javascript",
    "javascriptreact",
    "json",
    "latex",
    "less",
    "markdown",
    "php",
    "plaintext",
    "pug",
    "python",
    "restructuredtext",
    "rust",
    "scala",
    "scss",
    "text",
    "typescript",
    "typescriptreact",
    "yaml",
    "yml"
  ]
}
```

</details>

## Extension Release Process

This extension is built and published to the extension marketplace with GitHub Actions.

To publish a new version, create a new GitHub Release, bumping the tag version. This tag version will be used for the extension version.

Refer to the [github workflow](./.github/workflows/nodejs.yml).

## License

See [LICENSE.md](./LICENSE.md).
