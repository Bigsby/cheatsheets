# tmux shortcuts

## session
- List sessions
  ```
  tmux ls
  ```
- select session
  ```
  tmux attach-session -t «sessionNumber»
  ```
- `Ctrl-b d` - detach session/client

## window
- `Ctrl-b c` - new window
- `Ctrl-b «number»` - select window `«number»`
- `Ctrl-b ,` - rename window
- `Ctrl-b .` - renumber window
- `Ctrl-b Shit-Alt-x` - kill window
- `Shift+Left` or `Shift+Right` - select window

## pane
- `Ctrl-b %` - split horizontally
- `Ctrl-b "` - split vertically
- `Ctrl-b x` - kill pane
- `Ctrl-b Ctrl-Cursors` - resize
- `Ctrl-b Cursors` - select directional pane
- `Ctrl-b z` - toggle fullscreen


## copy-mode
- `Ctrl-b [` - Enter copy-mode. Vim visual-mode keys apply, including block.
  - `Space` - Start selection
  - `Esc` - Clear selection
  - `Enter` - Copy selection and quit
  - `q` - Quit
- `Ctrl-b ]` - Paste

## search buffer
- `Ctrl-b [` - Enter copy-mode. Vim visual-mode keys apply, including block.
  - `/` - search downwards
  - `?` - search upwards
  
