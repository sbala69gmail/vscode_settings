# VS CODE.

Hi Friends I have posted my VS code setting and plugins.  

## Setting list

```
{
  "workbench.iconTheme": "vscode-icons",
  "yaml.schemas": {
    "file:///c%3A/Users/balasubramani.s/.vscode/extensions/atlassian.atlascode-2.8.4/resources/schemas/pipelines-schema.json": "bitbucket-pipelines.yml"
  },
  //icons for files
  "vsicons.projectDetection.disableDetect": true,
  //for git setup
  "git.path": "C:\\laragon\\bin\\git\\mingw64\\bin\\git.exe", 
  //for php setup
  "php.validate.enable": true,
  "php.executablePath": "C:\\laragon\\bin\\php\\php-7.2.19-Win32-VC15-x64\\php.exe", 
  "php.validate.executablePath": "C:\\laragon\\bin\\php\\php-7.2.19-Win32-VC15-x64\\php.exe", 
  //common setup
  "editor.wordWrap": "on",
  "explorer.openEditors.visible": 0,
  "editor.minimap.enabled": false,
  "[apib]": {},
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 5000,
  "editor.formatOnSave": false,
  "editor.formatOnPaste": false, 
  //spell check exclude words
  "cSpell.userWords": [
    "Barryvdh",
    "Lumpsum",
    "Repo",
    "Spatie",
    "allfiles",
    "alphanum",
    "constrct",
    "deactive",
    "ernysans",
    "formly",
    "gridster",
    "incharge",
    "kubernetes",
    "laravel",
    "namespacing",
    "nuxt",
    "nuxtjs",
    "stylelint",
    "subfolder",
    "subfolders",
    "toastr",
    "unsignned",
    "vform"
  ], 
  //terminal setup
  "terminal.integrated.env.windows": {
    "CMDER_ROOT": "C:\\laragon\\bin\\cmder\\"
  },
  "breadcrumbs.enabled": false,
  "diffEditor.ignoreTrimWhitespace": false,
  "[typescript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[dart]": {
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.rulers": [
      80
    ],
    "editor.selectionHighlight": false,
    "editor.suggest.snippetsPreventQuickSuggestions": false,
    "editor.suggestSelection": "first",
    "editor.tabCompletion": "onlySnippets",
    "editor.wordBasedSuggestions": false
  },
  "[yaml]": {
    "editor.defaultFormatter": "redhat.vscode-yaml"
  },
  "liveServer.settings.donotShowInfoMsg": true,
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "javascript.format.insertSpaceBeforeFunctionParenthesis": true,
  "javascript.format.placeOpenBraceOnNewLineForControlBlocks": false,
  "javascript.format.placeOpenBraceOnNewLineForFunctions": false,
  "typescript.format.insertSpaceBeforeFunctionParenthesis": true,
  "typescript.format.placeOpenBraceOnNewLineForControlBlocks": false,
  "typescript.format.placeOpenBraceOnNewLineForFunctions": false,
  "vetur.format.defaultFormatter.html": "prettier",
  "vetur.format.defaultFormatter.js": "vscode-typescript",
  "auto-close-tag.enableAutoCloseTag": true,
  "php-cs-fixer.executablePath": "${extensionPath}/php-cs-fixer.phar",
  "php-cs-fixer.lastDownload": 1626956328815,
  "remote.SSH.configFile": "/c/Users/Windows/.ssh/config",
  "cSpell.enableFiletypes": [
    "vue"
  ],
  "vsicons.dontShowNewVersionMessage": true,
  "[php]": {
    "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
  },
  "window.zoomLevel": 1,
  "terminal.integrated.profiles.windows": {
    "Cmder": {
      "path": "${env:windir}\\System32\\cmd.exe",
      "args": ["/k", "C:\\laragon\\bin\\cmder\\vendor\\bin\\vscode_init.cmd"]
    }
  },
  "terminal.integrated.defaultProfile.windows": "Cmder",
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  
}

```

## Installed plugins

code --list-extensions | xargs -L 1 echo code --install-extension

```
code --install-extension alefragnani.project-manager
code --install-extension christian-kohler.path-intellisense
code --install-extension eamodio.gitlens
code --install-extension eridem.vscode-postman
code --install-extension esbenp.prettier-vscode
code --install-extension felixfbecker.php-intellisense
code --install-extension Gruntfuggly.todo-tree
code --install-extension Jarga.apib
code --install-extension MehediDracula.php-namespace-resolver
code --install-extension msjsdiag.debugger-for-chrome
code --install-extension PeterJausovec.vscode-docker
code --install-extension Shan.code-settings-sync
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension vncz.vscode-apielements
code --install-extension vscode-icons-team.vscode-icons
code --install-extension Zignd.html-css-class-completion
```
