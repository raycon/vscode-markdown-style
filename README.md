# vscode-markdown-css

> VSCode markdown css themes

## Markdown Preview Themes

Themes are based on VSCode's markdown default style :

```text
C:\Program Files (x86)\Microsoft VS Code\resources\app\extensions\markdown\media\markdown.css
```

- markdown-github.css : based on [@sinderesorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css)
- markdown-light.css
- markdown-dark-material.css : for [Material-theme](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)

## Markdown PDF Themes

Theme for [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf) extension. [markdown-pdf.css](markdown-pdf.css) overrides styles that defined by extension.

## Usage

Copy files to your computer. Edit `Settings.json` in [Settings File Location](https://code.visualstudio.com/Docs/customization/userandworkspace#_settings-file-locations) like below :

```json
"markdown.styles": [
    "[YOUR_PATH]/vscode-markdown-css/markdown-github.css"
],
"markdown-pdf.styles": [
    "[YOUR_PATH]/vscode-markdown-css/markdown-pdf.css"
]
```

## License

Licensed under the [MIT](LICENSE.md) License.