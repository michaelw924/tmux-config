# tmux Personal Configuration

Personal tmux configuration for michaelw924.

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/michaelw924/tmux-config.git ~/.tmux-config
   ln -s ~/.tmux-config/.tmux.conf ~/.tmux.conf
   ```

2. Reload tmux config:
   ```bash
   tmux source-file ~/.tmux.conf
   ```

## Features

- **Vi mode** for copy/scroll (vim-like motions)
- **Vim-like pane navigation** (h/j/k/l)
- **Vim-like prefix** (Ctrl+a instead of Ctrl+b)
- **Mouse support** enabled

## Keybindings

| Keybinding | Action |
|------------|--------|
| `C-a` | Tmux prefix |
| `C-a c` | New window |
| `C-a %` | Split vertically |
| `C-a "` | Split horizontally |
| `C-a h/j/k/l` | Navigate panes |
| `C-a x` | Kill pane |
| `C-a &` | Kill window |
| `C-a r` | Reload config |
| `Alt+h/j/k/l` | Resize panes (normal mode) |

## Files

- `.tmux.conf` - Main tmux configuration
