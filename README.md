Sublime Text 3
==============

Directory
---------
cd ~/Library/Application\ Support/Sublime\ Text\ 3

Keyboard shortcuts
------------------
```json
[
  {"keys": ["super+."], "command": "reveal_in_side_bar" },
  {"keys": ["super+v"], "command": "paste_and_indent"},
  {"keys": ["super+shift+v"], "command": "paste"},
  {"keys": ["ctrl+super+a"], "command": "alignment"},
  {"keys": ["super+shift+l"], "command": "sublimelinter_show_all_errors"},
  {"keys": ["super+alt+d"], "command": "consolewrap"},
  {"keys": ["alt+i"], "command": "expand_selection_to_quotes"},
  {"keys": ["alt+q"], "command": "change_quotes"},
  {"keys": ["super+alt+n"], "description": "advances new file"},
  {"keys": ["alt+up"], description: "Jump to previous indented line"},
  {"keys": ["alt+shift+up"], description: "Jump to previous indented line and extend selection"},
  {"keys": ["alt+down"], description: "Jump to next indented line"},
  {"keys": ["alt+shift+down"], description: "Jump to next indented line and extend selection"}
]
```

Plugins
-------
- Hasher
- HexViewer
- Advanced​New​File
- Git​Hubinator
- CTags

CTags - https://github.com/SublimeText/CTags
--------------------------------------------
rebuild_ctags -> ctrl+t, ctrl+r
navigate_to_definition -> ctrl+t, ctrl+t or ctrl+> or ctrl+shift+left_click
jump_prev -> ctrl+t, ctrl+b or ctrl+< or ctrl+shift+right_click
show_symbols -> alt+s
show_symbols (all files) -> alt+shift+s
show_symbols (suffix) -> ctrl+alt+shift+s
