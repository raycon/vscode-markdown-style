# vscode-markdown-css

> GitHub flavored markdown theme for vscode

## Files

- `github-markdown.css` from [@sinderesorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css)

The only change I made was to remove top level `.markdown-body` class from `github-markdown.css`

- `vscode-markdown.css`

It defines several classes to customize colors in light, dark and high-contrast themes. I override attributes by using values from `github-markdown.css`

## Getting Started

Copy files to your computer.

    git clone https://github.com/raycon/vscode-markdown-css.git

Edit `Settings.json` in [Settings File Location](https://code.visualstudio.com/Docs/customization/userandworkspace#_settings-file-locations)

    "markdown.styles": [
        "C:\\[YOUR_PATH]\\vscode-markdown-css\\github-markdown.css",
        "C:\\[YOUR_PATH]\\vscode-markdown-css\\vscode-markdown.css"
    ]

Restart VS Code

## License

Licensed under the [MIT](LICENSE.md) License.