# tmux shortcuts

## commands
Commands are run with `Ctrl-b :COMMAND`
- `list-commands`
- `list-keys`
- `kill-session`

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
- `Ctrl-b ?` - list key bindings

## window
- `Ctrl-b c` - new window
- `Ctrl-b «number»` - select window `«number»`
- `Ctrl-b ,` - rename window
- `Ctrl-b .` - renumber window
- `Ctrl-b Shit-Alt-x` - kill window
- `Ctrl-b p` - select previous window
- `Ctrl-b n` - select next window
- `Ctrl-b w` - select window from list
- `Ctrl-b l` - select previous window

## pane
- `Ctrl-b %` - split horizontally
- `Ctrl-b "` - split vertically
- `Ctrl-b x` - kill pane
- `Ctrl-b Ctrl-Cursors` - resize
- `Ctrl-b Cursors` - select directional pane
- `Ctrl-b z` - toggle fullscreen
- `Ctrl-b o` - swap panes


## copy-mode
- `Ctrl-b [` - Enter copy-mode. Vim visual-mode keys apply, including block.
  - `Space` - Start selection
  - `Esc` - Clear selection
  - `Enter` - Copy selection and quit
  - `q` - Quit
- `Ctrl-b ]` - Paste
### copy to x clipboard
```
echo "content to copy" | xclip -selection clipboard
```

## search buffer
- `Ctrl-b [` - Enter copy-mode. Vim visual-mode keys apply, including block.
  - `/` - search downwards
  - `?` - search upwards
  
