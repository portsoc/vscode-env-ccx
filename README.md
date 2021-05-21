# VS Code Environment for Code-Copy-Examples

This is a repository designed to give students a _quick start_ for stage one of the [code-copy-examples](https://portsoc.github.io/code-copy-examples).

It contains a **`package.json`** file that will help you automatically install the `prompt-sync` library.  To do this:
  1. Open the [integrated terminal](https://code.visualstudio.com/docs/editor/integrated-terminal])  (`ctrl`+`` ` ``)
  2. Type `npm install` in the opened terminal.

There's also a **workspace config** that helps you quickly run Javascript files.  To do this
  1. Open the [Command Palette](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette) (`ctrl`+`shift`+`p` on Windows, `cmd`+`shift`+`p` on Mac)
  2. Type `task runFile` in the opened menu.

You may also wish to make this a permanent **keyboard shortcut** by editing the `keybindings.json` file. To do this
  1. Open the Command Palette (`ctrl`+`shift`+`p` on Windows, `cmd`+`shift`+`p` on Mac)
  2. Type `Preferences: Open Keyboard Shortcuts (JSON) command.`
  3. Add the following lines within the square brackets (changing the value of `key` if you'd like a different key shortcut.)
```json
  {
    "key": "ctrl+j",
    "args": "runFile",
    "command": "workbench.action.tasks.runTask"
  },
```

