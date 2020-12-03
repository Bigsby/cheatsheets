# Vim shortcuts

## Search and Replace

### Search
```
:/seachPatern
```
*case sensitive* toggle `\c`

### Replace
```
:%s/oldWord/newWord/g
```

## Copy/Cut/Paste
- `V` - Enter visual mode
  - `Ctrl + v` - Enter block (vertical) mode
  - `y` - copy (yank)
  - `d` - cut
- ´p´ - paste, in normal mode
- ´P´ - paste to beginnig of line, in normal mode

## Undo / Redo
- `u` - Undo
- `Ctrl + r` - Redo


## Tabs
- New tab
  ```
  :tabnew «filename»
  ```
- `Ctrl + w Shit + t` - Pane to new tab
- `gt` - go to next tab
- `gT` - go to previous tab

## Windows (Panes)
- `:sp [filename]` - horizontal split
- `:vsp [filename]`- vertical split
- `Ctrl + w «cursor»` - select window in direction
- `Ctrl + w _` - toggle height maximize
- `Ctrl + w |` - toggle width maximize
- `Ctrl + w =` - normalize split sizes
- `Ctrl + w r` - swap windows (left-right, up-down)
- `Ctrl + w o` - close all windows
- `Ctrl + w +/-` - resize window vertically
- `Ctrl + w >/<` - resize window horizontally


"Close every window in the current tabview but the current one
Ctrl+W o

## Misc
- `Ctrl + G` - show current buffer file path
- `Ctrl + P` - list autocomplete options
- Set/change syntax highlight:
```
:setfiletype SYNTAX
```

## Configs
```
syntax on
set shiftwidth=4
set tabstop=4
set expandtab
set autoindent
```

