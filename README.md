# tmux cheat sheet
A handy collection of tmux shortcuts and tricks

Prefix key : Ctrl-b

## Session based
`Prefix + (` - switch to previous session
`Prefix + )` - switch to next session
`Prefix + L` - switch to the last used session
`Prefix + s` - show a list of all sessions to select
`Prefix + $` - rename the current session

### check if session exists. Returns 0 if exists else returns error
`tmux has-session <session-name>`

## window based
`Prefix + c` - creates a new window

## panes
`Prefix + %` - split panes horizontally
`Prefix + "` - split panes vertically
`Prefix + Arrow Key` - move to pane
`Prefix + ;` - move to previously active pane
`Prefix + o` - select next pane
`Prefix + z` - zoom/unzoom a pane (hides all other open panes)

### Resizing panes
`Prefix + Alt + Up/Down/Left/Right Arrow` - resize 5 spaces
`Prefix + Ctrl + Up/Down/Left/Right Arrow` - resize 1 space
