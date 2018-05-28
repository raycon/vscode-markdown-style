# vscode-markdown-css

> VSCode markdown css themes

## Markdown Preview Themes

Themes are based on VSCode's markdown default styles

    C:\Program Files\Microsoft VS Code\resources\app\extensions\markdown-language-features\media\markdown.css

## Themes

- Preview Theme

  - `markdown-light.` : light theme.
  - `markdown-github.css` : based on [@sinderesorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css)
  - `markdown-dark-material.css` : for [Material-theme](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)

- Extension Theme

  - `markdown-github-pandoc.html` : for vscode-pandoc extension
  - `markdown-pdf.css` : for MarkdownPDF extension

## Usage

- Copy css files to **root of your current workspace**.
- Edit `Settings.json` (**File > Preferences > Settings**) like below :

Github style:

```json
// Preview Settings
// Github style for all VSCode theme
"markdown.styles": [
    "markdown-github.css"
]
```

Light, Dark style:

```json
// Light/Dark style for Light/Dark VSCode theme
"markdown.styles": [
    "markdown-light.css",
    "markdown-dark-material.css"
]
```

[MarkdownPDF](https://github.com/yzane/vscode-markdown-pdf) style:

```json
// Extension - MarkdownPDF
"markdown-pdf.styles": [
    "[YOUR_PATH]/markdown-pdf.css"
]
```

[Pandoc] style:

```json
// Extension - vscode-pandoc
"pandoc.htmlOptString": "-s -f markdown_github -t html5 -H [YOUR_PATH]/markdown-github-pandoc.html",
```

## License

Licensed under the [MIT](LICENSE.md) License.