# kitty config

[kitty](https://sw.kovidgoyal.net/kitty/) terminal emulator setup: Catppuccin Mocha, Fira Code with ligatures, and tmux as the shell (tabs are tmux's job, so kitty's tab bar is hidden).

- `kitty.conf` — main config (theme, font features, macOS titlebar, tab shortcuts remapped/disabled)
- `themes/` — Catppuccin flavors + diff themes
- `icons/` — custom app icons (.icns)

Notable: `ctrl+shift+h/l` emit S-F1/S-F2 for tmux window switching, left Option acts as Alt for nvim, launches straight into `tmux new-session`.
