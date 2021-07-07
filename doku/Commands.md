## Window Shortcuts

| KEYS         | JSON                                             | DEFINITION                | USED |
| ------------ | ------------------------------------------------ | ------------------------- | ---- |
| ctrl+n       | workbench.action.files.newUntitledFile           | create new file           | x    |
| ctrl+t       | workbench.action.files.showOpenedFileInNewWindow | open file in new Window   | x    |
| ctrl+k f     | workbench.action.files.openFolder                | open new folder           | u    |
| ctrl+k w     | workbench.action.openWorkspace                   | open workspace            | u    |
| ctrl+k c     | workbench.action.closeFolder                     | close folder or workspace | u    |
| ctrl+k a     | workbench.action.addRootFolder                   | add folder to workspace   | u    |
| ctrl+alt+n   | workbench.action.newWindow                       | open new window           | x    |
| alt+q        | workbench.action.closeWindow                     | close window              | x    |
| ctrl+s       | workbench.action.files.save                      | save current file         | x    |
| ctrl+shift+s | workbench.action.files.saveAs                    | save file as              | x    |
| ctrl+o       | workbench.action.files.openFile                  | open file                 | x    |
| alt+#        | workbench.action.showCommands                    | open command menu         | x    |



## Window UI Elements
| KEYS     | JSON                                         | DEFINITION                    | USED |
| -------- | -------------------------------------------- | ----------------------------- | ---- |
| ctrl+e   | workbench.action.toggleSidebarVisibility     | open the left sidebar         | x    |
| ctrl+ß o | workbench.action.output.showOutput           | show  output                  | x    |
| ctrl+ß a | workbench.action.toggleActivityBarVisibility | show  activity bar            | x    |
| ctrl+ß m | editor.action.toggleMinimap                  | show  minimap                 | x    |
| ctrl+ß w | workbench.action.showErrorsWarnings          | show  warnings tab            | x    |
| ctrl+ß t | workbench.action.selectTheme                 | go to  the color theme menu   | x    |
| ctrl+.   | workbench.action.openSettingsJson            | switch to json view           | x    |
| alt+.    | workbench.action.openGlobalKeybindingsFile   | open key bindings as json     | x    |
| ctrl+k i | workbench.action.selectIconTheme             | open file icon theme          | x    |
| ctrl+k p | workbench.action.selectProductIconTheme      | open product icon theme       | x    |
| ctrl+ß b | workbench.action.toggleStatusbarVisibility   | toggle the footer (statusbar) | r    |



## Window Control Elements
| KEYS             | JSON                              | DEFINITION | USED |
|------------------|-----------------------------------|------------|------|
| f11              | workbench.action.toggleFullScreen | fullscreen | x    |
| ctrl+shift + "+" | workbench.action.zoomIn           | zoom in    | x    |
| ctrl+shift + "-" | workbench.action.zoomOut          | zoom out   | x    |


## MARKDOWN
| KEYS          | JSON                       | DEFINITION             |
|---------------|----------------------------|------------------------|
| ctrl+k m      | markdown.showPreviewToSide | open  markdown preview |
| ctrl+k ctrl+m | markdown.preview.refresh   | refresh  markdown      |



## DEBUG
| KEYS     | JSON                                 | DEFINITION        |
|----------|--------------------------------------|-------------------|
| f9       | editor.debug.action.toggleBreakpoint | add  break point  |
| f5       | workbench.action.debug.start         | run  program      |
| f5       | workbench.action.debug.continue      | continue  program |
| f6       | workbench.action.debug.pause         | pause  program    |
| shift+f5 | workbench.action.debug.stop          | stop  program     |



## TAB CONTROL

| KEYS              | JSON                                                        | DEFINTION                                      | USED |
| ----------------- | ----------------------------------------------------------- | ---------------------------------------------- | ---- |
| ctrl+h            | workbench.action.splitEditor                                | split current tab to side editor default split | x    |
| alt+h             | workbench.action.splitEditorLeft                            | split left                                     | x    |
| alt+j             | workbench.action.splitEditorDown                            | split bottom                                   | x    |
| alt+k             | workbench.action.splitEditorUp                              | split top                                      | x    |
| alt+l             | workbench.action.splitEditorRight                           | split right                                    | x    |
| ctrl+w            | workbench.action.closeActiveEditor                          | close  current tab                             | x    |
| ctrl+1 - ctrl+"n" | workbench.action.focusFirstEditor                           | switch  to editor by index                     | x    |
| alt+1 - alt+"n"   | workbench.action.openEditorAtIndex1                         | go to  tab in the current editor by index      | x    |
| ctrl+alt+f        | workbench.action.moveEditorToFirstGroup                     | move tab into first editor group               | x    |
| ctrl+alt+h        | workbench.action.moveEditorToLeftGroup                      | move tab to left group                         | x    |
| ctrl+alt+j        | workbench.action.moveEditorToBelowGroup                     | move tab to bottom group                       | x    |
| ctrl+alt+k        | workbench.action.moveEditorToAboveGroup                     | move tab to top group                          | x    |
| ctrl+alt+l        | workbench.action.moveEditorToRightGroup                     | move tab to left group                         | x    |
| ctrl+alt+e        | workbench.action.moveEditorToLastGroup                      | move tab to end group                          | x    |
| ctrl+alt+b        | workbench.action.moveEditorToPreviousGroup                  | move tab to before group                       | x    |
| ctrl+alt+n        | workbench.action.moveEditorToNextGroup                      | move tab to next group                         | x    |
| alt+b             | workbench.action.previousEditor                             | move to the left tab                           | x    |
| alt+n             | workbench.action.nextEditor                                 | move to the right tab                          | x    |
| ctrl+tab          | workbench.action.quickOpenPreviousRecentlyUsedEditorInGroup | switch tab by interface                        | x    |
| ctrl+shift+tab    | workbench.action.quickOpenLeastRecentlyUsedEditorInGroup    | switch tab by interface reverse                | x    |
| alt+shift+b       | workbench.action.moveEditorLeftInGroup                      | move current tab to previous place in group    | x    |
| alt+shift+n       | workbench.action.moveEditorRightInGroup                     | move current tab to next place in group        | x    |
| ctrl+alt+a        | workbench.action.closeEditorsInGroup                        | close all editors                              | x    |
| ctrl+alt+s        | workbench.action.closeUnmodifiedEditors                     | close saved editors in group                   | x    |


## TEXT EDIT

| KEYS         | JSON                               | DEFINTION               | USED |
| ------------ | ---------------------------------- | ----------------------- | ---- |
| ctrl+x       | editor.action.clipboardCutAction   | cut                     | x    |
| ctrl+c       | editor.action.clipboardCopyAction  | copy                    | x    |
| ctrl+v       | editor.action.clipboardPasteAction | paste                   | x    |
| ctrl+d       | editor.action.deleteLines          | delete  line            | x    |
| DownArrow    | cursorDown                         | move cursor down        | x    |
| RightArrow   | cursorRight                        | move  cursor right      | x    |
| LeftArrow    | cursorLeft                         | move  cursor left       | x    |
| UpArrow      | cursorUp                           | move  cursor up         | x    |
| ctrl+enter   | editor.action.insertLineAfter      | insert  line below      | x    |
| alt+enter    | editor.action.insertLineBefore     | insert  line above      | x    |
| ctrl+j       | editor.action.copyLinesDownAction  | duplicate line below    | x    |
| ctrl+shift+j | editor.action.copyLinesUpAction    | duplicate line above    | x    |
| ctrl+i       | editor.action.indentLines          | indent line             | x    |
| ctrl+u       | editor.action.outdentLines         | outdent line            | x    |
| ctrl+#       | editor.action.commentLine          | add single line comment | x    |
| ctrl+alt+#   | editor.action.blockComment         | add multi line comment  | x    |
| ctrl+z       | undo                               | undo                    | x    |
| ctrl+y       | redo                               | redo                    | x    |
| ctrl+a       | #no command needed                 | select whole text       | x    |



## SEARCH AND REPLACE OPTIONS

| KEYS         | JSON                                 | DEFINTION                                                    | USED |
| ------------ | ------------------------------------ | ------------------------------------------------------------ | ---- |
| ctrl+q       | editor.fold                          | fold  code //collides with Windows searchBar                 | x    |
| alt+q        | editor.unfold                        | unfold code                                                  | x    |
| ctrl+shift+q | editor.foldAll                       | fold all  code //collides with Windows searchBar //doestn work | x    |
| alt+shift+q  | editor.unfoldAll                     | unfold  all code //doesnt work                               | x    |
| ctrl+r       | editor.action.startFindReplaceAction | replace words                                                | x    |
| ctrl+shift+r | workbench.action.replaceInFiles      | replace words in multiple files                              | x    |
| ctrl+f       | actions.find                         | find  words // move it to vim                                | x    |
| ctrl+shift+f | workbench.action.findInFiles         | find  words in multiple files //same as ctrl+ß s             | x    |
| alt+w        | toggleSearchEditorWholeWord          | find the exact word                                          | x    |
| alt+r        | toggleSearchEditorRegex              | find with regex pattern                                      | x    |
| alt+c        | toggleSearchEditorCaseSensitive      | find case sensitive                                          | x    |



# VIM SECTION

## UI NAVIGATION - VIM (only work if workspace focus)
| KEY        | JSON                                        | DESCRIPTION                                  |
| ---------- | ------------------------------------------- | -------------------------------------------- |
| <leader>+e | workbench.view.explorer                     | toggle sidebar/explorer                      |
| <leader>+s | workbench.view.search                       | toggle sidebar/search                        |
| <leader>+x | workbench.view.extensions                   | toggle sidebar/extensions                    |
| <leader>+g | workbench.action.quickOpen                  | toggle open file popup                       |
| <leader>+f | editor.action.formatDocument                | format document                              |
| <leader>+h | powerHeader.insert                          | insert header to file                        |
| <leader>+d | workbench.view.debug                        | toggle sidebar/debug                         |
| <leader>+k | workbench.action.openGlobalKeybindings      | open keybindings page                        |
| <leader>+z | workbench.action.toggleZenMode              | toggle zen mode                              |
| <leader>+r | workbench.action.openRecent                 | open recent folders                          |
| <leader>+o | workbench.action.openSettings               | open vscode options -> switch to json ctrl+. |
| <leader>+t | workbench.action.terminal.toggleTerminal    | toggle intern terminal                       |
| <leader>+c | workbench.action.terminal.openNativeConsole | open external terminal                       |
| <leader>+w | workbench.action.closeUnmodifiedEditors     | close unchanged editors                      |



## UI NAVIGATION - VSCODE (only work if sidebar focus)

| KEY     | JSON                                        | DESCRIPTION                              |
| ------- | ------------------------------------------- | ---------------------------------------- |
| space+e | workbench.action.toggleSidebarVisibility    | close explorer                           |
| space+s | workbench.view.search                       | view search                              |
| space+x | workbench.view.extensions                   | view extensions                          |
| space+i | workbench.action.focusActiveEditorGroup     | focus editor                             |
| space+g | workbench.action.quickOpen                  | open file popup                          |
| space+d | workbench.view.debug                        | toggle sidebar/debug                     |
| space+z | workbench.action.toggleZenMode              | toggle zen mode                          |
| space+r | workbench.action.openRecent                 | open recent folders                      |
| space+o | workbench.action.openSettings               | open vscode options                      |
| space+k | workbench.action.openGlobalKeybindings      | open keybindings page                    |
| ESC     | workbench.action.focusActiveEditorGroup     | is needed to loose focus from text input |
| space+t | workbench.action.terminal.toggleTerminal    | toggle intern terminal                   |
| space+c | workbench.action.terminal.openNativeConsole | open external terminal                   |
| space+w | workbench.action.closeUnmodifiedEditors     | close unchanged editors                  |



## EXPLORER SHORTCUTS - VSCODE

| KEY     | JSON                                        | DESCRIPTION                  |
|---------|---------------------------------------------|------------------------------|
| o       | filesExplorer.openFilePreserveFocus         | open file under cursor       |
| r       | renameFile                                  | rename the file under cursor |
| l       | workbench.files.action.refreshFilesExplorer | reload file explorer         |
| shift+d | deleteFile                                  | delete the file under cursor |
| e       | revealFileInOS                              | open file in os explorer     |


## FILE EDITING - VIM
| KEY     | JSON                           | DESCRIPTION            |
|---------|--------------------------------|------------------------|
| space+s | workbench.action.files.save    | save current file      |
| space+a | workbench.action.files.saveAll | save all current files |

