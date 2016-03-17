[index]: https://github.com/rafaelrinaldi/cheatsheets
[jason]: https://twitter.com/jasonlong

# tmux

<img src=tmux.png width=320>

><sub>Logo proposed by [Jason Long][jason]</sub>

1. [CLI](#1.0)
1. [Defauts](#2.0)

---

### <a name='1.0'></a>CLI

| Option | Description |
| :--- | :--- |
| `ls` | List all active sessions |
| `attach -t n` | Attach to session `n` |
| `kill-session -t n` | Kill session `n` |

### <a name='2.0'></a>Defaults

| Command | Description |
| :--- | :--- |
| `Ctlr+B %` | Create a new vertical pane |
| `Ctrl+B "` | Create a new horizontal pane |
| `Ctrl+B [arrow]` | Move focus between panes |
| `Ctrl+B z` | Toggle current pane full screen mode |
| `Ctrl+B c` | Create a new window |
| `Ctrl+B n` | Move focus to window number `n` |
| `Ctrl+B d` | Detach from current session |
| `clear` or `Ctrl+l` | Clear current pane output (equivalent to <kbd>⌘</kbd> + <kbd>K</kbd>) |
| `Ctrl+B r` | Render UI |

---

[← Back][index]
