# Emacs CheatSheet

This sheet is a recopilation of what the team considered the most useful commands for Emacs for daily use. Feel free to enrich this knoledge base with your own favourite commands.

> Note: the *Meta* key has a different behavior depending of what operating system you are using. On OSX you can use the *ESCAPE* key as a modifier; on Linux and Windows the equivalent is the *Alt* key.

## Emacs

### Suspend Emacs

```emacs
Ctrl-z
```

### Exit permanently

```emacs
Ctrl-x Ctrl-c
```

### Advanced options

```emacs
Meta-x
```

## Files

### Open file

```emacs
Ctrl-x Ctrl-f
```

### Save changes

```emacs
Ctrl-x Ctrl-s
```

### Save changes on all open files

```emacs
Ctrl-x s
```

### Change currently open file for another in the same folder

```emacs
Ctrl-x Ctrl-v
```

## Error recovery

### Abort a command

```emacs
Ctrl-g
```

### Undo a change

```emacs
Ctrl-x u
```

Or...

```emacs
Ctrl-_
```

Or...

```emacs
Ctrl-/
```

## Incremental search

### Search forward (down)

```emacs
Ctrl-s
```

### Search backward (up)

```emacs
Ctrl-r
```

### Search and replace

```emacs
Meta-%
```

Then press 'y' for replace, or 'n' to skip to the next match, or 'q' to quit.

## Shells

### Start a new shell

```emacs
Meta-x
```

## Motion

### Go to line number...

```emacs
Meta-g Meta-g
```

## Selection

### Start a selection from the current position

```emacs
Ctrl-@
```

Or...

```emacs
Ctrl-SPACEBAR
```

### Select current paragraph

```emacs
Ctrl-h
```

### Select all

```emacs
Ctrl-x Ctrl-p
```

### Cut selection

```emacs
Ctrl-w
```

### Copy selection

```emacs
Meta-w
```

### Cut current line

```emacs
Ctrl-k
```

### Paste

```emacs
Ctrl-y
```

## Multiple windows

### Split window side by side

```emacs
Ctrl-x 3
```

### Split window above and below

```emacs
Ctrl-x 2
```

### Switch between windows

```emacs
Ctrl-x O
```

This use the letter 'O'.

### Close the current window

```emacs
Ctrl-x 0
```

This use the number '0' (zero).

### Close all the other windows

```emacs
Ctrl-x 1
```
