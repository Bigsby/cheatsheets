# Vim shortcuts

## Replace all occurences of word

```
:%s/oldWord/newWord/g
```

## Copy/Cut/Paste
- `V` - Enter visual mode
  - `Ctrl + v` - Enter block (vertical) mode
  - `y` - copy (yank)
  - `d` - cut
- ´p´ - paste, in normal mode

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

## Windows (Panes)
- `:sp [filename]` - horizontal split
- `:vsp [filename]`- vertical split
- `Ctrl + w «cursor»` - select window in direction
- `Ctrl + w _` - toggle height maximize
- `Ctrl + w |` - toggle width maximize
- `Ctrl + w =` - normalize split sizes
- `Ctrl + w r` - swap windows (left-right, up-down)
- `Ctrl + w o` - close all windows





"Close every window in the current tabview but the current one
Ctrl+W o