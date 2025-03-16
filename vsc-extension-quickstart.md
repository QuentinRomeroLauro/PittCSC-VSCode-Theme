# Welcome to PittCSC Theme

## What's in the folder

* `package.json` - this is the manifest file that defines the extension and its metadata
* `themes/pittcsc-theme-color-theme.json` - the color theme definition file

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded
* Open `File > Preferences > Color Themes` and pick your color theme
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac)

## Make changes

* Changes to the theme file are automatically applied to the Extension Development Host window
* You can relaunch the extension from the debug toolbar after making changes to the files listed above
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes

## Adopt your theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.
* To learn more about scopes and how they're used, check out the [VS Code theme documentation](https://code.visualstudio.com/docs/extensions/themes-snippets-colorizers)

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read about [publishing an extension](https://code.visualstudio.com/docs/extensions/publish-extension).

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/) 