# Vuejs Workbox

## A vuejs development environment setup to code with popular and useful vuejs extensions. I can assure you this will the last extension pack for vuejs development that you will ever be needed. Happy coding! Cheers!

#### Please read the recommended workplace settings to enable all extension features.

### Brief of included extensions

* [vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) -
  Vue tooling for VS Code, powered by vue-language-server.

* [vue-peek](https://marketplace.visualstudio.com/items?itemName=dariofuzinato.vue-peek) -
  This extension extends Vue code editing with Go To Definition and Peek Definition support for components and filenames in single-file components with a .vue extension. It allows quickly jumping to or peeking into files that are referenced as components (from the template), or as module imports

* [auto-rename-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) -
  Automatically rename paired HTML/XML tag, same as Visual Studio IDE does.

* [auto-close-tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) -
  Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text does.

* [npm](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) -
  This extension supports running npm scripts defined in the package.json file and validating the installed modules against the dependencies defined in the package.jso

* [NPM IntelliSense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) -
  Visual Studio Code plugin that autocompletes npm modules in import statements

* [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) -
  VS Code package to format your JavaScript / TypeScript / CSS using Prettier.

* [Sorting HTML and Jade attributes](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-attrs-sorter) -
  Sorting of the tag attributes in the specified order.
* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer) -
  This extension allows matching brackets to be identified with colours. The user can define which characters to match, and which colours to use.
* [Import Cost VSCode](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) - This extension will display inline in the editor the size of the imported package. The extension utilizes webpack with babili-webpack-plugin in order to detect the imported size.

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates [ESLint](http://eslint.org/) into VS Code. If you are new to ESLint check the [documentation](http://eslint.org/).

* [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode) - Quokka.js is a rapid prototyping playground in your editor, with access to your project’s files, inline reporting, code coverage and rich output formatting.
[documentation](https://quokkajs.com/docs/).

* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - GitLens supercharges the Git capabilities built into Visual Studio Code. It helps you to visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more.

* [Highlight TODO, FIXME, or whatever annotations.](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight) - Another plugin to ensure maintainability of your scalable project. Highlight TODO, FIXME, or whatever annotations.

* [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons) - Love to see relatable file/folder icons? This will bring beautiful icons to your folder/files.

* [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.javascriptsnippets) - This extension contains code snippets for JavaScript in ES6 syntax for Vs Code editor (supports both JavaScript and TypeScript). Code snippets are also supported with vuejs files.

## Paste these recommended settings in VS code workspace settings to supercharged your vs code.

```
{
  "eslint.enable": true,
  "window.zoomLevel": 1,
  "files.trimTrailingWhitespace": true,
  "prettier.singleQuote": true,
  "prettier.trailingComma": "es5",
  "prettier.eslintIntegration": true,
  "prettier.disableLanguages": [],
  "eslint.autoFixOnSave": true,
  "editor.insertSpaces": true,
  "editor.formatOnSave": true, // only if you want auto      //fomattting on saving the file
  "editor.detectIndentation": true,
  "editor.tabSize": 2,
  "editor.formatOnPaste": false,
  "editor.formatOnType": true,
  "editor.renderControlCharacters": true,
  "editor.renderWhitespace": "all",
  "files.exclude": {
    "**/node_modules": true
  },
  "eslint.validate": [
    {
      "autoFix": true,
      "language": "javascript"
    },
    {
      "autoFix": true,
      "language": "vue"
    }
  ]
}
```

* Todo Extension Settings:

```

[{
    pattern: "TODO:",
    style: {
    dark: {
        color: "#757575"
    },
    light: {
        color: "#fff"
    },
    backgroundColor: "#ffbd2a",
    borderRadius: "2px",
    border: "1px solid red"
    },
    description: "Things need to be done later."
},
{
    pattern: "FIXME:",
    style: {
    dark: {
        color: "#eee"
    },
    light: {
        color: "#fff"
    },
    backgroundColor: "#f06292",
    borderRadius: "2px",
    border: "1px solid red"
    },
    description: "Things need to be fixed."
},
"AVOID:",
"BUG:",
"CAUTION:",
"CONFIGURATION:",
"DEBUG:",
"DEPRECATED:",
"DO_NOT_REMOVE:",
"HACK:",
"IMPORTANT:",
"IMPROVE:",
"INFO:",
"ISSUE:",
"KEEP:",
"LEGACY:",
"NOTE:",
"OPTIMIZE:",
"PERFORMANCE:",
"PLACEHOLDER:",
"PREFER:",
"REFACTOR:",
"REMOVE:",
"REVIEW:",
"RFC:",
"TEMP:",
"WARNING:"
]
```



## Credits

* Vuejs workbox has created with the help of above mention plugins. Thanks go to the original authors and contributors of the above mentioned plugin.

**Enjoy!**

> Feel free to send pull requests with updates.

```

```
