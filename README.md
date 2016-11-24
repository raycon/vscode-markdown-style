# vscode-markdown-css

> VSCode markdown css theme based on [@sinderesorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css)

## Files

```text
vscode-markdown-css
 ├ css
 │  ├ github-markdown.css    : .markdown-body class removed.
 │  └ common.css             : Common styles.
 │
 ├ markdown-github.css       : LIGHT
 └ markdown-material.css     : DARK
```

## Usage

Copy files to your computer.

    git clone https://github.com/raycon/vscode-markdown-css.git

Edit `Settings.json` in [Settings File Location](https://code.visualstudio.com/Docs/customization/userandworkspace#_settings-file-locations)

```json
"markdown.styles": [
    // For light theme
    "[YOUR_PATH]/vscode-markdown-css/markdown-github.css",
    // For dark theme
    "[YOUR_PATH]/vscode-markdown-css/markdown-material.css"
]
```

Restart VS Code

## License

Licensed under the [MIT](LICENSE.md) License.