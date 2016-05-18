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
| `<Prefix> s` | List available sessions |
| `<Prefix> $` | Rename session |
| `<Prefix> d` | Detach from current session |
| `<Prefix> c` | Create a new window |
| `<Prefix> w` | List all windows |
| `<Prefix> n` | Move focus to next window |
| `<Prefix> p` | Move focus to previous window |
| `<Prefix> f` | Find window |
| `<Prefix> ,` | Rename window |
| `<Prefix> &` | Destroy window |
| `<Prefix> [0-9]` | Move focus to window index |
| `<Prefix> %` | Create a new vertical pane |
| `<Prefix> "` | Create a new horizontal pane |
| `<Prefix> q` | Display a list of pane numbers |
| `<Prefix> o` | Switch focus between panes |
| `<Prefix> [arrow]` | Move focus to specific pane |
| `<Prefix> {` | Move current pane to the left |
| `<Prefix> }` | Move current pane to the right |
| `<Prefix> z` | Toggle current pane full screen mode |
| `<Prefix> x` | Destroy pane |
| `clear` or `Ctrl+l` | Clear current pane output (equivalent to <kbd>⌘</kbd> + <kbd>K</kbd>) |
| `<Prefix> r` | Render UI |
| `<Prefix> [` | Enter scroll mode |
| `q` | Exit scroll mode |

---

[← Back][index]
