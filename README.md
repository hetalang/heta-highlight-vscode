[![Heta project](https://img.shields.io/badge/%CD%B1-Heta_project-blue)](https://hetalang.github.io/)
[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/insysbio.heta-highlight-vscode)](https://marketplace.visualstudio.com/items?itemName=insysbio.heta-highlight-vscode)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/insysbio.heta-highlight-vscode)
![GitHub](https://img.shields.io/github/license/insysbio/heta-highlight-vscode)

# heta-highlight-vscode package

The package is plugin for [Visual Studio Code](https://code.visualstudio.com/) editor to highlight the Heta language code.

This is part of [Heta project](https://hetalang.github.io/).

## Installation from VS Marketplace

1) From VSCode menu: **Extensions (Ctrl+ Shift +X) -> Search -> "heta"**
2) It is recommended to use "Dark+" or "Light+" theme. See File -> Preferences -> Color Theme

## Development mode

Press F5

## Publishing in VS Marketplace

```bash
# npm i
# npx vsce login
npx vsce publish # or npm run publish
```

## Converting to .sublime-syntax

### Way 1 - Sublime only

1. Install Sublime text: https://www.sublimetext.com/3
2. Open Sublime text with file `./syntaxes/heta.json`
3. Install Package Control: https://packagecontrol.io/installation
4. Tools => Command Palette... (ctrl+shift+p in Windows), type `install package`
5. Select and install `PackageDev`
6. Tools => Command Palette... (ctrl+shift+p in Windows), type `PackageDev: Convert (YAML...`, Convert to property list
7. Rename `heta.plist` to `heta.tmLanguage`
8. Tools => Developer => New Syntax from heta.tmLanguage
9. Save file `heta.sublime-syntax` to C:\Users\<user>\AppData\Roaming\Sublime Text 3\Packages\User

### Way 2 - VSCode

1. in VSCOde install Package `TextMate Languages`
2. View => Command Palette (ctrl+shift+p in Windows) type: `Convert to tmLanguage PLIST...`
3. Save to `heta.tmLanguage` and use Sublime for other actions (#8)

## Screenshot
![Screenshot of the package](./screen0.png)
