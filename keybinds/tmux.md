# Tmux

## CLI commands
### Attach to last session
`tmux a`

#### Attach to session
`tmux a -t <session_id or name>`

### Start new session with name
`tmux new -s <name>`

### List sessions
`tmux ls`

### Kill session
tmux kill-session -t <name or id>

## Pane commands
### Split pane vertical
`<leader> %`

### Split pane horizontal
`<leader> "`

### Move to pane at index
`<leader> q <index number>`

### Kill pane
`<leader> x`

### Toggle zoom on pane
`<leader> z`

## Window commands
### Break pane into window
`<leader> !`

### Create window
`<leader> c`

### Kill window
`<leader> &`

### Move windows
`<leader> n or p`

### Change windows
`<leader> <window number>`

### List windows
`<leader> w`

## Editor commands
### Edit command in editor(neovim)
`ctrl-x ctrl-e`

### Enter copy mode
`<leader> [`

## Copy mode
### Start selection
`space`

### Paste contents to buffer
`<leader> ]`

### Search forward
`/`

### Search backward
`?`

## Session commands

### Detach from session
`<leader> d`

### Change sessions
`<leader> ( or )`

### Rename session
`<leader> $`

### List shortcuts
`<leader> ?`

