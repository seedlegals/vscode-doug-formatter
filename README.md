# VS Code Doug formatter 

This plugin adds syntax highlighting for Doug template files in VS Code. 

It supports the vue syntax and HTML DOM events.


# Install and run


Install webpack and ts-loader

```
npm i --save-dev webpack webpack-cli ts-loader
```

Compile the extension

```
npm run webpack
```

Open this folder in VS Code.

Edit `package.json` so that `"main"` points to `"./dist/extension"`.

Run the extension by pressing F5.

# Based on:
1) vscode-pug-formatter (https://github.com/alexbabichev/vscode-pug-formatter)
2) vscode-formatter-sample (https://github.com/jrieken/vscode-formatter-sample)
3) vetur (https://github.com/vuejs/vetur)
4) vscode-angular-pug (https://github.com/ghaschel/vscode-angular-pug)

# License

MIT
Original work © 2019 Alex Babichev  
