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
| `new -s beep` | Create a new session named `beep` |
| `new -c boop` | Create a new window named `boop` |
| `ls` | List all active sessions |
| `attach` | Attach to last active session |
| `attach -t beep` | Attach to session `beep` |
| `kill-session -t boop` | Kill session `boop` |

### <a name='2.0'></a>Defaults

| Command | Description |
| :--- | :--- |
| `<Prefix> %` | Create a new vertical pane |
| `<Prefix> "` | Create a new horizontal pane |
| `<Prefix> [arrow]` | Move focus between panes |
| `<Prefix> z` | Toggle current pane full screen mode |
| `<Prefix> c` | Create a new window |
| `<Prefix> n` | Move focus to window number `n` |
| `<Prefix> d` | Detach from current session |
| `clear` or `Ctrl+l` | Clear current pane output (equivalent to <kbd>⌘</kbd> + <kbd>K</kbd>) |
| `<Prefix> r` | Render UI |

---

[← Back][index]
