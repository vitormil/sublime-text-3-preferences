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
  {"keys": ["alt+up"], "description": "Jump to previous indented line"},
  {"keys": ["alt+shift+up"], "description": "Jump to previous indented line and extend selection"},
  {"keys": ["alt+down"], "description": "Jump to next indented line"},
  {"keys": ["alt+shift+down"], "description": "Jump to next indented line and extend selection"}
]
```

Plugins
-------
- Alignment
- All autocomplete
- AutoFileName
- ChangeQuotes
- Clickable URLs
- ColorPicker
- Console Wrap for JS
- Emmet
- Emmet CSS Snippets
- FileSystem Autocompletion https://github.com/lingo/sublime-fscompletion
- FindKeyConflicts https://github.com/skuroda/FindKeyConflicts
- Git https://github.com/kemayo/sublime-text-git
- GitGutter https://github.com/jisaacks/GitGutter
- Git​Hubinator https://github.com/ehamiter/ST2-GitHubinator
- Hayaku (tools for writing CSS faster) https://github.com/hayaku/hayaku
- Jump Along Indent https://github.com/mwean/sublime_jump_along_indent
- LESS https://github.com/danro/LESS-sublime
- SASS https://github.com/nathos/sass-textmate-bundle
- SideBarEnhancements https://github.com/titoBouzout/SideBarEnhancements
- Expand selection to quotes https://github.com/kek/sublime-expand-selection-to-quotes
- Sublime Linter (jshint, json, ruby, csslint)
  - http://sublimelinter.readthedocs.org
  - https://github.com/SublimeLinter/SublimeLinter-jshint
  - https://github.com/SublimeLinter/SublimeLinter-json
  - https://github.com/SublimeLinter/SublimeLinter-ruby
  - https://github.com/SublimeLinter/SublimeLinter-csslint
- Hasher https://github.com/dangelov/hasher
- HexViewer https://github.com/facelessuser/HexViewer
- Advanced​New​File https://github.com/skuroda/Sublime-AdvancedNewFile
- CTags https://github.com/SublimeText/CTags

CTags
-----
| Command                  | Shortcut |
| ------------------------ | -------- |
| rebuild_ctags            | -> ctrl+t, ctrl+r |
| navigate_to_definition   | -> ctrl+t, ctrl+t or ctrl+> or ctrl+shift+left_click |
| jump_prev                | -> ctrl+t, ctrl+b or ctrl+< or ctrl+shift+right_click |
| show_symbols             | -> alt+s |
| show_symbols (all files) | -> alt+shift+s |
| show_symbols (suffix)    | -> ctrl+alt+shift+s |
