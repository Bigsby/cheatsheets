# Vim shortcuts

## Search and Replace

### Search
```
:/seachPatern
```
*case sensitive* toggle `\c`

- `*` - search word under cursor

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

## Navigation
- `:N` - Go to line `N`
- `Ctrl + o` - Go to previous location
- `Ctrl + i` - Go to newer location
- `Ctrl + y/e` - Scroll up/down
- `{` / `}` - Move to previous/next empty line
- `%` - Move to matching enclosing _()_, _{}_, _[]_

"Close every window in the current tabview but the current one
Ctrl+W o

## Misc
- `Ctrl + x, Ctrl + f` - autocomplete file system
- `Ctrl + g` - show current buffer file path
- `Ctrl + p`, `Ctrl + n` - list autocomplete options
- `Ctrl + v, Tab` - Insert TAB (for Makefile)
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

