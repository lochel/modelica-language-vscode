# Modelica in Visual Studio Code

This extension adds support for the Modelica language to Visual Studio Code.


## Source

Both grammar and snippets are imported from this [implementation](https://github.com/BorisChumichev/modelicaSublimeTextPackage) in SublimeText.


## Features

### Colorization

![colorization](https://github.com/SimplyDanny/modelica-language-vscode/raw/master/images/colorization.png)

### Snippets

![snippets-editor](https://github.com/SimplyDanny/modelica-language-vscode/raw/master/images/snippets-editor.png)

![snippets-command-palette](https://github.com/SimplyDanny/modelica-language-vscode/raw/master/images/snippets-command-palette.png)

## Usage

### Install the extension in VS Code

* Open the command palette using `Ctrl+Shift+P`
* Type `ext install Modelica` in the command palette

### Select Modelica as a language

* On the bottom-right corner, click on the *select language mode* button, if you have created a new file it should display *Plain Text*
* Select *Modelica* in the list of languages.

Alternatively, saving the file with a `.mo` or `.mos` extension will allow VS Code to understand that it is a Modelica file and automatically select the language correctly.
Additional extensions can be connected to the language in any `settings.json` file using the `"files.associations"` setting.

### Using snippets

Just start to type and choose a snippet that may be proposed. Alternatively, use `Ctrl+Shift+P` to open the command palette and type `Insert Snippet` to see a list of all possible snippets to choose from.
