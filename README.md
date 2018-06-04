# VS Code Config
My VS Code configuration

## Key Bindings ## 

``` javascript
[
    { 
        "key": "ctrl+shift+r",
        "command": "workbench.action.quickOpen" 
    },

    { 
        "key": "ctrl+d",
        "command": "editor.action.clipboardCutAction",
        "when": "textInputFocus && !editorReadonly" 
    },

    { 
        "key": "ctrl+shift+s",
        "command": "workbench.action.files.saveAll" 
    },

    {
        "key": "ctrl+alt+down",
        "command": "editor.action.copyLinesDownAction"
    },

    {
        "key": "alt+shift+f",
        "command": "editor.action.reindentlines"
    },

    {
        "key": "ctrl+shift+c",
        "command": "editor.action.addCommentLine"
    }
]
```

## User Settings ##

``` javascript
{
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
    "workbench.colorTheme": "Material Theme",
    "materialTheme.fixIconsRunning": false,
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorCustomizations": {
        "activityBarBadge.background": "#80CBC4",
        "list.activeSelectionForeground": "#80CBC4",
        "list.inactiveSelectionForeground": "#80CBC4",
        "list.highlightForeground": "#80CBC4",
        "scrollbarSlider.activeBackground": "#80CBC450",
        "editorSuggestWidget.highlightForeground": "#80CBC4",
        "textLink.foreground": "#80CBC4",
        "progressBar.background": "#80CBC4",
        "pickerGroup.foreground": "#80CBC4",
        "tab.activeBorder": "#80CBC4",
        "notificationLink.foreground": "#80CBC4",
        "editor.findWidgetResizeBorder": "#80CBC4",
        "editorWidget.border": "#80CBC4"
    },
    "materialTheme.accentPrevious": "Indigo",
    "window.zoomLevel": 0,
    "materialTheme.accent": "Teal",
    "materialTheme.autoApplyIcons": true,
    "editor.mouseWheelZoom": true
}
```
