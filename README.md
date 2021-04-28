# VS Code Environment for Code-Copy-Examples

This is a repository designed to give students a quick start for stage 1 of the [code-copy-examples](https://portsoc.github.io/code-copy-examples).

It contains a `package.json` file to get the necessary modules with `npm install`, as well as a workspace config for Visual Studio Code.

This config contains a specific task to quickly run Javascript files. 
To run that task, press `Ctrl+P` (`Cmd+P` on a Mac) and type `task runFile` in the opened menu.

You can also add a permanent shortcut (`Ctrl-J`) by adding the following inside your VS Code `keybindings.json` file. You can open the file in VS Code by going to Keyboard Shortcuts (`Ctrl-K Ctrl-S`, or `Cmd-K Cmd-S` on a Mac) and clicking the file button at the top-right.

```json
  {
    "key": "ctrl+j",
    "args": "runFile",
    "command": "workbench.action.tasks.runTask"
  },
```

Change the value of `key` if you'd like a different key shortcut.
