# my-vscode-settings
My preferred configuration for vscode

![](preview.png)

## Contents

* Terminal color scheme
* Settings for text editor
* Hack font (must be installed on the system)

## Settings
```json
{
    "editor.fontFamily": "Hack",
    "window.autoDetectColorScheme": true,
    "editor.suggestSelection": "first",
    "workbench.colorCustomizations": {
      "terminal.foreground": "#FFFFFF",
      "terminal.background": "#1E1E1E",
      "terminal.ansiBlack": "#1E1E1E",
      "terminal.ansiBrightBlack": "#504F54",
      "terminal.ansiRed": "#FE4A49",
      "terminal.ansiBrightRed": "#FE4A49",
      "terminal.ansiGreen": "#86FDB8",
      "terminal.ansiBrightGreen": "#86FDB8",
      "terminal.ansiYellow": "#FDA331",
      "terminal.ansiBrightYellow": "#FDA331",
      "terminal.ansiBlue": "#70D6FF",
      "terminal.ansiBrightBlue": "#70D6FF",
      "terminal.ansiMagenta": "#E000B4",
      "terminal.ansiBrightMagenta": "#E000B4",
      "terminal.ansiCyan": "#00F5DC",
      "terminal.ansiBrightCyan": "#00F5DC",
      "terminal.ansiWhite": "#B8B8B8",
      "terminal.ansiBrightWhite": "#B8B8B8"
    },
    "editor.rulers": [80,120],
    "editor.renderWhitespace": "all",
    "editor.tokenColorCustomizations": null,
  }
```

## Usage

Copy the contents of `settings.json` entirely or partially and paste it within your local `settings.json` file
