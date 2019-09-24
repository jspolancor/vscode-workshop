# Developing and publishing Visual Studio Code extensions

## Intro

VsCode is great, but you could make it greater

## You can

- Change the look of VS Code with a color or icon theme - Theming
- Add custom components & views in the UI - Extending the Workbench
- Create a Webview to display a custom webpage built with HTML/CSS/JS
- Support a new programming language - Language Extensions Overview

### What you usually would do

- Register commands
- Display notifications
- Collect user input
- Create code snippets
- Connect to external servers

## What we will create

Develop an extension that will execute saved commands on the vscode integrated terminal

## Developing the extension

1. The easiest way to start developing vscode extensions is to clone the [hello world example](https://github.com/microsoft/vscode-extension-samples/tree/master/helloworld-minimal-sample)

2. Open the official VsCode [extension API docs](https://code.visualstudio.com/api)

3. Inside the package.json file you should register how your extension contributes to vscode.
in the contributes key you register the commands and configuration for the extension

4. Go to the extension.js file and add the functionality to the commands

## Publishing

Publishing is an easy but tedious proccess.

Just follow the [official instructions](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) and be patient.