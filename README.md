# vscode-markdown-css

> VSCode markdown css themes

Themes are based on VSCode's markdown default styles

    C:\Program Files\Microsoft VS Code\resources\app\extensions\markdown-language-features\media\markdown.css

## Themes

- Preview Theme

  - `light-default.css` : light theme.
  - `dark-material.css` : for [Material-theme](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)
  - `github.css` : based on [@sinderesorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css)

- Extension Theme

  - `pandoc-github.html` : for vscode-pandoc extension
  - `markdown-pdf.css` : for MarkdownPDF extension

## Usage

- Copy css files to **root of your current workspace**.
- Edit `Settings.json` (**File > Preferences > Settings**) like below :

Github style:

```json
// Preview Settings
// Github style for all VSCode theme
"markdown.styles": [
    "github.css"
]
```

Light, Dark style:

```json
// Light/Dark style for Light/Dark VSCode theme
"markdown.styles": [
    "light-default.css",
    "dark-material.css"
]
```

MarkdownPDF style:

```json
// Extension - MarkdownPDF
"markdown-pdf.styles": [
    "[YOUR_PATH]/markdown-pdf.css"
]
```

Pandoc style:

```json
// Extension - vscode-pandoc
"pandoc.htmlOptString": "-s -f markdown_github -t html5 -H [YOUR_PATH]/pandoc-github.html",
```

## License

Licensed under the [MIT](LICENSE.md) License.