# Best Back End Sublime Text Plugins

* Origami (for multiple panels on the same window)
* Pretty JSON
* Trailing Spaces
* Trimmer
* SideBarGit
* [SublimeREPL](https://github.com/wuub/SublimeREPL)
* [SublimeCodeIntel](https://github.com/SublimeCodeIntel/SublimeCodeIntel)

## PHP

* SublimePHPCS
* SublimePHPIntel

### WordPress

### Laravel

* Laravel Blade Highlighter

## Ruby

### Rails

## Some good snippets

### Goto on right-click

Create a file named "`Default (Linux).sublime-mousemap`" at `Packages/User/` folder. Change **Linux** to your OS (Windows|Linux|OS X), if necessary.

Using your editor, put this configuration:

```json
[
    {
        "button": "button2",
        "count": 1,
        "modifiers": ["ctrl"],
        "press_command": "drag_select",
        "command": "goto_definition"
    }
]
```

Save it and restart Sublime. Now you can right-click in some function and go to their implementation!
