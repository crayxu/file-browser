# File Browser

Language and tools:
- Kotlin 1.5
- OpenJDK 11
- JavaFX 11
- IntelliJ

Due to the university policy, the source code is available only for education and employment purpose. There is a demo video of this project:

[File Browser Demo Video](https://youtu.be/pz9d35xVyaQ)

![File Browser](/file-browser.png)

The following are core requirements:

- The left-hand side will display a list of files and directories.
- When launched, this list should show the contents of a test folder that is included in your project (referred to as Home below). The user can use navigate through this list using keyboard shortcuts, toolbar buttons, or menu options.
- User should be able to scroll up and down the list of files using arrow keys to change the selectged file, or select an entry by clicking on it with a pointing device. The status line should always display the path and filename of the selected item.
- Users should be able to descend into a directory, using a hotkey (Enter), or a toolbar button (Next) or a menu item, or by double-clicking with a pointing device.
- Users should be able to navigate up to the parent directory using a hotkey (Backspace or Delete), or a toolbar button (Prev) or a menu item.
- Users should be able to return to the Home directory at any time by pressing a button on the toolbar or selecting a corresponding menu item.
- User can perform file-manipulation operations:
- Users should be able to rename a file or directory, by selecting the item, and then pressing a rename icon on the toolbar, or selecting Action - Rename from the -menu bar. You should prompt the user for the new name. If they provide an invalid name, you should display an error and cancel the rename operation.
- Users should be able to move a file or directory to a different location, by selecting an item, and then pressing a move icon on the toolbar, or selecting Action Move from the menu bar. You should prompt the user for the destination directory with a dialog box, and display an error if the destination is invalid.
- Users should be able to delete a file or directory, by selecting the item, and then pressing a delete icon on the toolbar, or selecting Action - Delete from the menu bar. You must prompt the user with a confirmation dialog before proceeding (i.e. ask them if they wish to delete the item, and given them a chance to cancel out of this operation).
- User can show or hide hidden files:
There should be a toggle option on the menubar Option - Show Hidden Files that determines if hidden files are shown or not. It should default to hiding hidden files. [NOTE: for the purposes of this assignment, a hidden file is considered to be any file that starts with a period .]. Changing this option should immediately be reflected in the file list, and should persist as the user navigates.
The right-hand side will display the content of the selected file:
- If a directory is selected, you should show a blank page for the contents.
- If the selected file is an image (i.e. extension is png, jpg, bmp) then you should display the image sized to fit the window.
- If the selected file is text (i.e. extension is txt, md) then you should display the contents of the file. The contents window should have a scrollbar if the file requires more than a single screen to display.
- If the file is any other type, or an unknown type, show a blank page for the contents.
- If the file is unreadable for any reason (e.g. insufficent permissions), you should show a blank page, or provide some indication that the file contents cannot be loaded.
- The status line should show details about the selected file, including the full path and filename. You may choose to add more information if you wish, but it is not required.
