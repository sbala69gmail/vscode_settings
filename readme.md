# VS CODE.

Hi Friends I have posted my VS code setting and plugins.  

## Setting list

```
{
  //for git setup
  "git.path": "E:\\laragon\\bin\\git\\mingw64\\bin\\git.exe",
  //for php setup
  "php.validate.enable": true,
  "php.executablePath": "E:\\laragon\\bin\\php\\php-7.2.11-Win32-VC15-x64\\php.exe",
  //common setup
  "editor.wordWrap": "on",
  "explorer.openEditors.visible": 0,
  "editor.minimap.enabled": false,
  "[apib]": {},
  "window.zoomLevel": 1,
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 5000,
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  //icons for files
  "vsicons.projectDetection.disableDetect": true,
  //spell check exclude words
  "cSpell.userWords": ["Repo", "constrct", "deactive", "unsignned"],
  //terminal setup
  "terminal.external.windowsExec": "E:\\laragon\\bin\\cmder\\Cmder.exe",
  "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\cmd.exe",
  "terminal.integrated.shellArgs.windows": [
    "/K E:\\laragon\\bin\\cmder\\vendor\\init.bat"
  ],
  "terminal.integrated.env.windows": {
    "CMDER_ROOT": "E:\\laragon\\bin\\cmder\\"
  }
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
