## VS Code Settings

# Font - Theme

* [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)
* [Theme - Seti-Monokai](https://marketplace.visualstudio.com/items?itemName=SmukkeKim.theme-setimonokai)
* [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

# Extensions

* [advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=coenraads.bracket-pair-colorizer)
* [ES7 React/Redux/GrapQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
* [GitLens-Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
* [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
* [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
* [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
* [Theme - Seti-Monokai](https://marketplace.visualstudio.com/items?itemName=SmukkeKim.theme-setimonokai)
* [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
* [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

# Settings

```json
{
    "editor.tabSize": 2,
    "editor.fontSize": 20,
    "editor.fontFamily": "Anonymous Pro",
    "terminal.integrated.fontSize": 22,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[css]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "workbench.colorCustomizations": {
        "activityBarBadge.background": "#0084ff",
        "list.activeSelectionForeground": "#C6FF00",
        "list.inactiveSelectionForeground": "#C6FF00",
        "list.highlightForeground": "#C6FF00",
        "scrollbarSlider.activeBackground": "#C6FF0050",
        "editorSuggestWidget.highlightForeground": "#C6FF00",
        "textLink.foreground": "#C6FF00",
        "progressBar.background": "#C6FF00",
        "pickerGroup.foreground": "#C6FF00",
        "tab.activeBorder": "#0084ff",
        "notificationLink.foreground": "#C6FF00",
        "editorWidget.resizeBorder": "#C6FF00",
        "editorWidget.border": "#C6FF00",
        "settings.modifiedItemIndicator": "#C6FF00",
        "settings.headerForeground": "#C6FF00",
        "panelTitle.activeBorder": "#C6FF00",
        "breadcrumb.activeSelectionForeground": "#C6FF00",
        "menu.selectionForeground": "#C6FF00",
        "menubar.selectionForeground": "#C6FF00",
        "editor.findMatchBorder": "#C6FF00",
        "selection.background": "#C6FF0040"
    },
    "editor.tokenColorCustomizations": {
    },
    "materialTheme.accent": "Acid Lime",
    "prettier.eslintIntegration": true,
    "prettier.singleQuote": true,
    "prettier.semi": true,
    "emmet.includeLanguages": {
        "javascript": "javascriptreact",
        "vue-html": "html"
    },
    "window.zoomLevel": 0,
    "workbench.colorTheme": "Seti Monokai",
    "workbench.iconTheme": "vscode-icons",
    "auto-rename-tag.activationOnLanguage": [
        "html",
        "xml",
        "php",
        "javascript"
    ],
    "eslint.validate": [
        {
            "language": "vue",
            "autoFix": true
        },
        {
            "language": "html",
            "autoFix": true
        },
        {
            "language": "javascript",
            "autoFix": true
        }
    ]
}
```

# Keywords

* Advanced new file: ctrl + alt + n
* Showandrun command: ctrl + shift + p
* Linux code format: ctrl + shift + i
* Linux comment out: ctrl + shift + 6
* Linux duplicate code: ctrl + shift + alt + up, down

# Showandrun Commands 
  -ctrl + shift + p
  
* quokka: start on current file
* format document(prettier)
* ES7 snippet search
