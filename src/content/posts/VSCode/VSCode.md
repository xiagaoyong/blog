---
title: VSCode settings
published: 2024-05-10
description: 'VSCode 配置'
image: ""
tags: [IDE,VSCode]
category: 'IDE'
draft: false 
---
```json
{
    "editor.fontSize": 18,
    "editor.fontVariations": true,
    "editor.fontLigatures": true,
    "editor.fontWeight": "normal",
    "workbench.colorTheme": "One Dark Pro",
    "editor.fontFamily": "Fira Code",
    "[typescriptreact]": {
        "editor.defaultFormatter": "aaron-bond.better-comments"
    },
    "[typescript]": {
        "editor.defaultFormatter": "aaron-bond.better-comments"
    },
    "[css]": {
        "editor.defaultFormatter": "aaron-bond.better-comments"
    },
    "security.workspace.trust.untrustedFiles": "open",
    "markdown-pdf.breaks": true,
    "docker.containers.label": "ContainerId",
    "docker.commands.run": "${containerCommand} run --rm -d ${exposedPorts} ${tag}",
    "[javascript]": {
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "security.workspace.trust.enabled": false,
    "cmake.configureOnOpen": true,
    "C_Cpp.autocompleteAddParentheses": true,
    "qtForPython.designer.path": "‪F:\\Qt\\6.6.1\\mingw_64\\bin\\designer.exe",
    "pyqt-integration.qtdesigner.path": "‪F:\\Qt\\6.6.1\\mingw_64\\bin\\designer.exe",
    "qtConfigure.qtDir": "f:\\Qt",
    "qtConfigure.mingwPath": "f:\\Qt/Tools/mingw0_64",
    "cmake.options.statusBarVisibility": "visible",
    "cmake.options.advanced": {
        "build": {
            "statusBarVisibility": "visible"
        },
        "launch": {
            "statusBarVisibility": "visible"
        },
        "debug": {
            "statusBarVisibility": "visible"
        }
    },
    "cmake.showOptionsMovedNotification": false,
    "[cpp]": {
        "editor.defaultFormatter": "llvm-vs-code-extensions.vscode-clangd"
    },
    "C_Cpp.intelliSenseEngine": "disabled",
    "files.autoGuessEncoding": true,
    "editor.mouseWheelZoom": true,
    "editor.formatOnPaste": true,
    "editor.formatOnSave": true,
    "editor.formatOnType": true,
    "editor.wordWrap": "on",
    "editor.acceptSuggestionOnEnter": "smart",
    "window.dialogStyle": "custom",
    "debug.showBreakpointsInOverviewRuler": true,
    "remote.SSH.remotePlatform": {
        "172.245.126.14": "linux",
        "141.98.196.134": "linux"
    },
    "files.autoSave": "onFocusChange",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.cursorBlinking": "smooth",
    "editor.smoothScrolling": true,
    "workbench.list.smoothScrolling": true,
    "terminal.integrated.smoothScrolling": true,
    "z-reader.fileDir": "F:\\Book",
    "cmake.showConfigureWithDebuggerNotification": false,
    "cmake.showNotAllDocumentsSavedQuestion": false,
    "workbench.colorCustomizations": {
        "terminal.background": "#1D1F21",
        "terminal.foreground": "#C5C8C6",
        "terminalCursor.background": "#C5C8C6",
        "terminalCursor.foreground": "#C5C8C6",
        "terminal.ansiBlack": "#1D1F21",
        "terminal.ansiBlue": "#3971ED",
        "terminal.ansiBrightBlack": "#969896",
        "terminal.ansiBrightBlue": "#3971ED",
        "terminal.ansiBrightCyan": "#3971ED",
        "terminal.ansiBrightGreen": "#198844",
        "terminal.ansiBrightMagenta": "#A36AC7",
        "terminal.ansiBrightRed": "#CC342B",
        "terminal.ansiBrightWhite": "#FFFFFF",
        "terminal.ansiBrightYellow": "#FBA922",
        "terminal.ansiCyan": "#3971ED",
        "terminal.ansiGreen": "#198844",
        "terminal.ansiMagenta": "#A36AC7",
        "terminal.ansiRed": "#CC342B",
        "terminal.ansiWhite": "#C5C8C6",
        "terminal.ansiYellow": "#FBA922"
    },
    "[c]": {
        "editor.defaultFormatter": "xaver.clang-format"
    },
    "files.autoSaveDelay": 5000,
    "clangd.checkUpdates": true,
}

