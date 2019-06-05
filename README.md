# computer-setup
Setting up a new computer docs

## Git Completion Bash
[link](https://github.com/git/git/blob/master/contrib/completion/git-completion.bash)

Create file on root `.git-completion.bash`

update `.bash_profile` with 

```
if [ -f ~/.git-completion.bash ]; then
  . ~/.git-completion.bash
fi
```

## Command Prompt

Command prompt colors:
- Slot 1: Red: 78, Green: 154, Blue: 6
- Slot 2: Red: 114, Green: 159, Blue: 207
- Slot 3: Red: 48, Green: 10, Blue: 36
- Slot 4: Red: 6, Green: 152, Blue: 154
- Slot 5: Red: 204, Green: 0, Blue: 0
- Slot 6: Red: 117, Green: 80, Blue: 123
- Slot 7: Red: 196, Green: 160, Blue: 0
- Slot 8: Red: 211, Green: 215, Blue: 207
- Slot 9: Red: 85, Green: 87, Blue: 83
- Slot 10: Red: 114, Green: 159, Blue: 207
- Slot 11: Red: 138, Green: 226, Blue: 52
- Slot 12: Red: 52, Green: 226, Blue: 226
- Slot 13: Red: 239, Green: 41, Blue: 41
- Slot 14: Red: 173, Green: 127, Blue: 168
- Slot 15: Red: 252, Green: 233, Blue: 79
- Slot 16: Red: 238, Green: 238, Blue: 238

“Screen Text” and “Popup Background” set to  slot 16 and “Screen Background” and “Popup Text” set to slot 3.

## VS Code settings.json

```
"workbench.colorCustomizations": {
    "terminal.foreground": "#eeeeee",
    "terminal.ansiGreen": "#000",
    "terminal.background": "#000" 
}
```

