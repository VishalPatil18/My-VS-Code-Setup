# My VS Code Setup

## Themes and Icon Pack
- [Tinacious Design theme](https://marketplace.visualstudio.com/items?itemName=tinaciousdesign.theme-tinaciousdesign)
- [VSCode Great Icons](https://github.com/DavidBabel/vscode-simpler-icons)

 
## Extensions
- [C/C++](https://code.visualstudio.com/docs/languages/cpp)
- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
- [Customize UI](https://marketplace.visualstudio.com/items?itemName=iocave.monkey-patch)
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Python](https://code.visualstudio.com/docs/python/python-tutorial#_prerequisites)
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)


## Settings.json
```
{
    "python.pythonPath": "/Library/Developer/CommandLineTools/usr/bin/python3",
    "jupyter.alwaysTrustNotebooks": true,
    "extensions.autoUpdate": false,
    "python.autoUpdateLanguageServer": false,
    "extensions.autoCheckUpdates": false,
    "code-runner.clearPreviousOutput": true,
    "code-runner.runInTerminal": true,
    "code-runner.saveFileBeforeRun": true,
    "editor.accessibilitySupport": "off",

    "code-runner.executorMap": {
        "javascript": "node",
        "java": "cd $dir && javac $fileName && java $fileNameWithoutExt",
        "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "objective-c": "cd $dir && gcc -framework Cocoa $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "php": "php",
        "python": "python3",
        "perl": "perl",
        "perl6": "perl6",
        "ruby": "ruby",
        "go": "go run",
        "lua": "lua",
        "groovy": "groovy",
        "powershell": "powershell -ExecutionPolicy ByPass -File",
        "bat": "cmd /c",
        "shellscript": "bash",
        "fsharp": "fsi",
        "csharp": "scriptcs",
        "vbscript": "cscript //Nologo",
        "typescript": "ts-node",
        "coffeescript": "coffee",
        "scala": "scala",
        "swift": "swift",
        "julia": "julia",
        "crystal": "crystal",
        "ocaml": "ocaml",
        "r": "Rscript",
        "applescript": "osascript",
        "clojure": "lein exec",
        "haxe": "haxe --cwd $dirWithoutTrailingSlash --run $fileNameWithoutExt",
        "rust": "cd $dir && rustc $fileName && $dir$fileNameWithoutExt",
        "racket": "racket",
        "scheme": "csi -script",
        "ahk": "autohotkey",
        "autoit": "autoit3",
        "dart": "dart",
        "pascal": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
        "d": "cd $dir && dmd $fileName && $dir$fileNameWithoutExt",
        "haskell": "runhaskell",
        "nim": "nim compile --verbosity:0 --hints:off --run",
        "lisp": "sbcl --script",
        "kit": "kitc --run",
        "v": "v run",
        "sass": "sass --style expanded",
        "scss": "scss --style expanded",
        "less": "cd $dir && lessc $fileName $fileNameWithoutExt.css",
        "FortranFreeForm": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fortran-modern": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fortran_fixed-form": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "fortran": "cd $dir && gfortran $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt"
    },
    "json.schemas": [],
    "css.lint.unknownAtRules": "ignore",
    
    "customizeUI.activityBarHideSettings":true,
    "customizeUI.fontSizeMap": {
        "13px": "13px",
        "12px": "12px",
        "window-title": "13px", // Window title font when using custom titlebar
        "tab-title": "13px",    // Used for editor tab titles
        "monospace": "13px",  // Used for monospace fonts in user interface
        "menu": "13px",         // Used for menu items (windows only)
    },
    "customizeUI.stylesheet": {
        ".search-view .search-widgets-container": "padding-top: 0px !important",
        ".suggest-input-container": "padding: 3px 4px 3px !important;"
    },
    "customizeUI.titleBar": "inline",
    "window.titleBarStyle": "native",
    "editor.find.addExtraSpaceOnTop": false,
    "editor.fontFamily": "Monaco",
    "editor.cursorBlinking": "solid",
    "workbench.tips.enabled": false,
    "workbench.tree.indent": 10,
    "workbench.tree.renderIndentGuides": "none",
    "window.newWindowDimensions": "inherit",
    "scm.diffDecorations": "gutter",
    "scm.diffDecorationsGutterVisibility": "hover",
    "editor.lineHeight": 24,
    "window.title": "${rootName}",
    "window.zoomLevel": 0,
    "customizeUI.activityBar":"bottom",
    "customizeUI.listRowHeight": 22,
    "diffEditor.ignoreTrimWhitespace": false,
    "terminal.integrated.fontSize": 13,
    "terminal.integrated.fontFamily": "MesloLGS NF",
    "terminal.external.osxExec": "iTerm.app",
    "terminal.explorerKind": "external",
    "terminal.integrated.shell.osx": "/bin/zsh",
    "workbench.iconTheme": "vscode-great-icons",
    "workbench.colorTheme": "Tinacious Design (legacy, 2016)",
    "editor.minimap.enabled": false,
    "breadcrumbs.enabled": false,
    "editor.fastScrollSensitivity": 8,
    "editor.fontSize": 14,
    "debug.console.fontSize": 13,
    "editor.wordWrap": "on",
    "notebook.kernelProviderAssociations": [],
    "update.mode": "none",
}
```

## Screenshots
<img src="https://raw.githubusercontent.com/SpecTEviL/My-VS-Code-Setup/main/ActivityBar%20Open.png">
<img src="https://raw.githubusercontent.com/SpecTEviL/My-VS-Code-Setup/main/ActivityBar%20Closed.png">


**Shortcut to Close/Open Activity Bar -** *"ctrl/cmd + B"*
