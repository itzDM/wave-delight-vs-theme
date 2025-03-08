### About Theme

#### this theme have Three color theme

- WD Light
- WD Dark Modern
- WD Dark Cool


### About Theme

#### this theme have Three color theme

- WD Light
- WD Dark Modern
- WD Dark Cool

## Copy This Keyboard Shortcut Key And Paste in keybinding.json

- Press ctrl+shift+p -->Search -->open default keyboard Shortcuts (JSON)-->paste given code

```

// Place your key bindings in this file to override the defaults
[
  {
    "key": "ctrl+alt+n",
    "command": "editor.action.addSelectionToNextFindMatch",
    "when": "editorFocus"
  },
  {
    "key": "ctrl+d",
    "command": "-editor.action.addSelectionToNextFindMatch",
    "when": "editorFocus"
  },
  {
    "key": "ctrl+shift+a",
    "command": "-codeium.openChatView",
    "when": "false"
  },
  {
    "key": "ctrl+shift+a",
    "command": "-editor.action.blockComment",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+a",
    "command": "-notification.acceptPrimaryAction",
    "when": "notificationFocus || notificationToastsVisible"
  },
  {
    "key": "ctrl+alt+a",
    "command": "workbench.action.toggleActivityBarVisibility"
  },
  {
    "key": "ctrl+shift+e",
    "command": "-workbench.view.explorer",
    "when": "viewContainer.workbench.view.explorer.enabled"
  },
  {
    "key": "ctrl+shift+e",
    "command": "-workbench.action.quickOpenNavigatePreviousInFilePicker",
    "when": "inFilesPicker && inQuickOpen"
  },
  {
    "key": "ctrl+shift+e",
    "command": "workbench.view.explorer"
  },
  {
    "key": "ctrl+shift+t",
    "command": "-workbench.action.reopenClosedEditor"
  },
  {
    "key": "ctrl+shift+t",
    "command": "workbench.view.extension.thunder-client"
  },
  {
    "key": "ctrl+shift+r",
    "command": "-workbench.view.extension.thunder-client"
  },
  {
    "key": "ctrl+shift+r",
    "command": "workbench.action.reopenClosedEditor"
  },
  {
    "key": "ctrl+d",
    "command": "editor.action.copyLinesDownAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+alt+down",
    "command": "-editor.action.copyLinesDownAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+d",
    "command": "-workbench.view.debug",
    "when": "viewContainer.workbench.view.debug.enabled"
  },
  {
    "key": "ctrl+shift+d",
    "command": "editor.action.copyLinesUpAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+alt+up",
    "command": "-editor.action.copyLinesUpAction",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+oem_7",
    "command": "workbench.action.toggleFullScreen",
    "when": "!isIOS"
  },
  {
    "key": "f11",
    "command": "-workbench.action.toggleFullScreen",
    "when": "!isIOS"
  },
  {
    "key": "alt+oem_comma",
    "command": "workbench.files.action.createFileFromExplorer"
  },
  {
    "key": "ctrl+alt+f",
    "command": "workbench.files.action.createFolderFromExplorer"
  },
  {
    "key": "ctrl+shift+a",
    "command": "editor.action.selectHighlights",
    "when": "editorFocus"
  },
  {
    "key": "ctrl+shift+l",
    "command": "-editor.action.selectHighlights",
    "when": "editorFocus"
  },
  {
    "key": "ctrl+alt+a",
    "command": "-codeium.openChatView",
    "when": "true"
  },
  {
    "key": "ctrl+q",
    "command": "-workbench.action.quit"
  },
  {
    "key": "ctrl+shift+q",
    "command": "editor.fold",
    "when": "editorTextFocus && foldingEnabled"
  },
  {
    "key": "ctrl+shift+[",
    "command": "-editor.fold",
    "when": "editorTextFocus && foldingEnabled"
  },
  {
    "key": "alt",
    "command": "-focusPreviousRenameSuggestion",
    "when": "renameInputFocused && renameInputVisible"
  },
  {
    "key": "shift+delete",
    "command": "-deleteFile",
    "when": "filesExplorerFocus && foldersViewVisible && !explorerResourceReadonly && !inputFocus"
  },
  {
    "key": "shift+delete",
    "command": "editor.action.deleteLines",
    "when": "textInputFocus && !editorReadonly"
  },
  {
    "key": "ctrl+shift+k",
    "command": "-editor.action.deleteLines",
    "when": "textInputFocus && !editorReadonly"
  },
  {
    "key": "alt+m",
    "command": "workbench.action.toggleMenuBar"
  },
  {
    "key": "ctrl+k ctrl+w",
    "command": "workbench.action.closeAllGroups"
  },
  {
    "key": "ctrl+k ctrl+shift+w",
    "command": "-workbench.action.closeAllGroups"
  },
  {
    "key": "ctrl+alt+\\",
    "command": "workbench.action.closeWindow"
  },
  {
    "key": "ctrl+shift+w",
    "command": "-workbench.action.closeWindow"
  },
  {
    "key": "ctrl+shift+w",
    "command": "workbench.action.closeAllEditors"
  },
  {
    "key": "ctrl+k ctrl+w",
    "command": "-workbench.action.closeAllEditors"
  },
  {
    "key": "ctrl+alt+e",
    "command": "codeium.explainCodeBlock"
  },
  {
    "key": "ctrl+alt+s",
    "command": "-mdb.runSelectedPlaygroundBlocks",
    "when": "mdb.isPlayground"
  },
  {
    "key": "ctrl+shift+s",
    "command": "workbench.action.files.saveFiles"
  },
  {
    "key": "ctrl+shift+s",
    "command": "-workbench.action.files.saveAs"
  },
  {
    "key": "ctrl+shift+s",
    "command": "-workbench.action.files.saveLocalFile",
    "when": "remoteFileDialogVisible"
  },
  {
    "key": "ctrl+alt+s",
    "command": "workbench.action.files.saveWithoutFormatting"
  },
  {
    "key": "ctrl+k ctrl+shift+s",
    "command": "-workbench.action.files.saveWithoutFormatting"
  },
  {
    "key": "ctrl+shift+oem_2",
    "command": "editor.action.blockComment",
    "when": "editorTextFocus && !editorReadonly"
  },
  {
    "key": "shift+alt+a",
    "command": "-editor.action.blockComment",
    "when": "editorTextFocus && !editorReadonly"
  }
]



```

## Copy This Setting And Paste in setting.json

- Press ctrl+shift+p -->Search -->open User Setting (JSON)-->paste given code

```

{
  "terminal.integrated.env.linux": {},
  "window.commandCenter": false,
  "editor.wordWrap": "on",
  "editor.mouseWheelZoom": true,
  "terminal.integrated.mouseWheelZoom": true,
  "editor.minimap.enabled": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "notebook.defaultFormatter": "esbenp.prettier-vscode",
  "notebook.formatOnSave.enabled": true,
  "editor.foldingImportsByDefault": false,
  "typescript.preferences.preferTypeOnlyAutoImports": true,
  "workbench.iconTheme": "material-icon-theme",
  "editor.codeActionsOnSave": {
    "source.organizeImports": "explicit"
  },
  "window.menuBarVisibility": "toggle",
  "workbench.sideBar.location": "left",
  "explorer.confirmDelete": false,
  "editor.stickyScroll.enabled": false,
  "workbench.colorTheme": "WD Dark Cool",
  "git.openRepositoryInParentFolders": "never",
  "emmet.includeLanguages": {
    "django-html": "html"
  },
  "editor.linkedEditing": true,
  "editor.formatOnSave": true,
  "terminal.integrated.fontSize": 25,
  "print.folder.includeFileList": true,
  "editor.inlayHints.enabled": "offUnlessPressed",
  "security.workspace.trust.untrustedFiles": "open",
  "[java]": {
    "editor.defaultFormatter": "redhat.java"
  },
  "java.edit.smartSemicolonDetection.enabled": true,
  "workbench.colorCustomizations": {
    "terminal.foreground": "#4a852dc2",
    "editorCursor.foreground": "#e10f0f"
  },
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyleInactive": "line",
  "terminal.integrated.cursorWidth": 3,
  "editor.overtypeCursorStyle": "line",
  "editor.cursorWidth": 3,
  "explorer.confirmDragAndDrop": false,
  "window.restoreWindows": "none",
  "update.mode": "start",
  "extensions.autoUpdate": false,
  "extensions.autoCheckUpdates": false,
  "python.languageServer": "Pylance",
  "explorer.confirmPasteNative": false,
  "git.autofetch": true
}



```

Notes:

- If Italic style not work, please install "Fira Code iScript" font
- And add this in setting.json -
  - "editor.fontFamily": "Fira Code iScript",
  - "editor.fontLigatures": true,

[GitHub](https://github.com/itzDm)

**Enjoy!**


Notes:

- If Italic style not work, please install "Fira Code iScript" font
- And add this in setting.json -
  - "editor.fontFamily": "Fira Code iScript",
  - "editor.fontLigatures": true,

[GitHub](https://github.com/itzDm)

**Enjoy!**
