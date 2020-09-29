# VSCode-config
My VSCode config.Feel free to adopt it if you like it.

Copy the config from here

```json
// Theme color Classes can be found here!!!
//https://code.visualstudio.com/api/references/theme-color
{
  "workbench.startupEditor": "newUntitledFile",
  "workbench.iconTheme": "material-icon-theme",
  "editor.formatOnSave": true,
  "terminal.integrated.shell.osx": "/bin/zsh",
  "window.zoomLevel": 0,
  "editor.fontSize": 17,
  "explorer.confirmDelete": false,
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "workbench.colorTheme": "Ninja Ui Vibrant",
  "explorer.confirmDragAndDrop": false,
  "editor.fontFamily": "Menlo, Monaco, 'Courier New', monospace, Menlo",
  "workbench.colorCustomizations": {
    "inputValidation.errorBackground": "#1D252C",
    "inputValidation.errorBorder": "#bbbbbb"
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": ["support.constant.property-value.css"],
        "settings": {
          "foreground": "#4695FF"
        }
      },
      {
        "scope": ["constant.numeric"],
        "settings": {
          "foreground": "#2CC7DA"
        }
      },
      {
        "scope": ["keyword.other.unit"],
        "settings": {
          "foreground": "#2CC7DA"
        }
      },
      {
        "scope": ["support.type.property-name"],
        "settings": {
          "foreground": "#B275FF"
        }
      },
      {
        "scope": ["variable.parameter.function"],
        "settings": {
          "foreground": "#F76693"
        }
      }
    ]
  }
}

```
