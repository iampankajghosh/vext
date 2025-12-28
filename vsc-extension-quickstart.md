# Nexus Dark - Development Guide

## What's in the folder

* This folder contains all of the files necessary for the Nexus Dark color theme extension.
* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/nexus-dark.json` - the color theme definition file.
* `README.md` - documentation and installation instructions.
* `CHANGELOG.md` - version history and changes.
* `LICENSE` - MIT license file.

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Open the color theme picker with the `File > Preferences > Theme > Color Theme` menu item, or use the `Preferences: Color Theme` command (`Ctrl+K Ctrl+T` / `Cmd+K Cmd+T`) and pick **Nexus Dark**.
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Make changes

* Changes to the theme file (`themes/nexus-dark.json`) are automatically applied to the Extension Development Host window.
* **Note:** Do not modify files in the `themes/` folder unless you're intentionally updating the theme colors.

## Theme Development

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

## Install your extension

* To start using your extension with Visual Studio Code, copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/api/working-with-extensions/publishing-extension about publishing an extension.
