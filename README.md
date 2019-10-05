# VSCode Extension Pack for Richard Willis

Search for "Richard Willis Extension Pack" in the extensions panel in vscode to install.

👉 [Create your own extension pack](https://code.visualstudio.com/blogs/2017/03/07/extension-pack-roundup)

## Setup

```bash
brew tap homebrew/cask-fonts
brew install font-fira-code shellcheck
```

## Settings

<details><summary>Recommended VS Code Settings</summary>

```json
{
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[dockerfile]": {
    "editor.defaultFormatter": "foxundermoon.shell-format"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
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
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[shellscript]": {
    "editor.defaultFormatter": "foxundermoon.shell-format"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[xml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[yaml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "breadcrumbs.enabled": true,
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
  ],
  "editor.cursorBlinking": "smooth",
  "editor.cursorSmoothCaretAnimation": true,
  "editor.detectIndentation": true,
  "editor.fontFamily": "Fira Code, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": false,
  "editor.fontSize": 13,
  "editor.formatOnSave": false,
  "editor.insertSpaces": true,
  "editor.renderWhitespace": "all",
  "editor.smoothScrolling": true,
  "editor.suggestSelection": "first",
  "editor.tabSize": 2,
  "eslint.autoFixOnSave": true,
  "explorer.confirmDragAndDrop": false,
  "files.insertFinalNewline": true,
  "files.trimTrailingWhitespace": true,
  "gitlens.codeLens.enabled": false,
  "go.enableCodeLens": {
    "references": false,
    "runtest": true
  },
  "html.suggest.html5": true,
  "html.validate.scripts": true,
  "html.validate.styles": true,
  "java.configuration.checkProjectSettingsExclusions": false,
  "java.configuration.updateBuildConfiguration": "automatic",
  "java.implementationsCodeLens.enabled": true,
  "java.referencesCodeLens.enabled": true,
  "jest.autoEnable": false,
  "jest.debugCodeLens.showWhenTestStateIn": [
    "fail",
    "unknown",
    "pass"
  ],
  "jest.pathToJest": "npm test --",
  "python.jediEnabled": false,
  "stylelint.config": {
    "ignoreFiles": [
      "**/*.js",
      "**/*.jsx"
    ]
  },
  "telemetry.enableCrashReporter": false,
  "telemetry.enableTelemetry": false,
  "terminal.external.osxExec": "iTerm.app",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "window.zoomLevel": 1,
  "workbench.colorCustomizations": {
    "statusBar.background": "#000000",
    "statusBar.noFolderBackground": "#000000"
  },
  "workbench.settings.enableNaturalLanguageSearch": false,
  "workbench.startupEditor": "newUntitledFile"
}
```

</details>

## Extensions

* https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint
* https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
* https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens
* https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
* https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
* https://marketplace.visualstudio.com/items?itemName=flowtype.flow-for-vscode
* https://marketplace.visualstudio.com/items?itemName=foxundermoon.shell-format
* https://marketplace.visualstudio.com/items?itemName=GabrielBB.vscode-lombok
* https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete
* https://marketplace.visualstudio.com/items?itemName=mkaufman.HTMLHint
* https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker
* https://marketplace.visualstudio.com/items?itemName=ms-python.python
* https://marketplace.visualstudio.com/items?itemName=ms-vscode.Go
* https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome
* https://marketplace.visualstudio.com/items?itemName=naco-siren.gradle-language
* https://marketplace.visualstudio.com/items?itemName=orta.vscode-jest
* https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml
* https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml
* https://marketplace.visualstudio.com/items?itemName=rogalmic.bash-debug
* https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint
* https://marketplace.visualstudio.com/items?itemName=slb235.vscode-coffeelint
* https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker
* https://marketplace.visualstudio.com/items?itemName=timonwong.shellcheck
* https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines
* https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack
* https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-test
* https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3


## Extension Release Process

This extension is built and published to the extension marketplace with GitHub Actions.

To publish a new version, create a new GitHub Release, bumping the tag version. This tag version will be used for the extension version.

Refer to the [github workflow](./.github/workflows/nodejs.yml).

## License

See [LICENSE.md](./LICENSE.md).
