# Keybindings

Leader key: `<Space>`

## General

| Keymap | Mode | Action |
|---|---|---|
| `<Esc>` | Normal | Clear search highlights |
| `<Esc><Esc>` | Terminal | Exit terminal mode |
| `<Space>q` | Normal | Open diagnostic quickfix list |
| `-` | Normal | Open parent directory (Oil) |
| `<Space>f` | Any | Format buffer |

## Window Navigation

| Keymap | Mode | Action |
|---|---|---|
| `Ctrl+h` | Normal | Move focus to left window |
| `Ctrl+l` | Normal | Move focus to right window |
| `Ctrl+j` | Normal | Move focus to lower window |
| `Ctrl+k` | Normal | Move focus to upper window |

## Telescope (Search/Find)

| Keymap | Mode | Action |
|---|---|---|
| `<Space>ff` | Normal | Find files |
| `<Space>,` | Normal | Switch buffers |
| `<Space><Space>` | Normal | Switch buffers (alias) |
| `<Space>sf` | Normal | Search files |
| `<Space>sg` | Normal | Live grep (search text) |
| `<Space>sh` | Normal | Search help tags |
| `<Space>sk` | Normal | Search keymaps |
| `<Space>ss` | Normal | Search Telescope pickers |
| `<Space>sw` | Normal/Visual | Search current word |
| `<Space>sd` | Normal | Search diagnostics |
| `<Space>sr` | Normal | Resume last search |
| `<Space>s.` | Normal | Search recent files |
| `<Space>sc` | Normal | Search commands |
| `<Space>sn` | Normal | Search Neovim config files |
| `<Space>/` | Normal | Fuzzy search in current buffer |
| `<Space>s/` | Normal | Live grep in open files |

## LSP (available when a language server attaches)

| Keymap | Mode | Action |
|---|---|---|
| `grn` | Normal | Rename symbol |
| `gra` | Normal/Visual | Code action |
| `grD` | Normal | Go to declaration |
| `grr` | Normal | Go to references |
| `gri` | Normal | Go to implementation |
| `grd` | Normal | Go to definition |
| `grt` | Normal | Go to type definition |
| `gO` | Normal | Document symbols |
| `gW` | Normal | Workspace symbols |
| `<Space>th` | Normal | Toggle inlay hints |

## Autocomplete (blink.cmp)

Uses the `default` preset.

| Keymap | Mode | Action |
|---|---|---|
| `Ctrl+y` | Insert | Accept completion |
| `Ctrl+n` / `Down` | Insert | Next item |
| `Ctrl+p` / `Up` | Insert | Previous item |
| `Ctrl+Space` | Insert | Open menu / show docs |
| `Ctrl+e` | Insert | Hide menu |
| `Ctrl+k` | Insert | Toggle signature help |
| `Tab` / `Shift+Tab` | Insert | Navigate snippet fields |

## Which-key Groups

| Prefix | Group |
|---|---|
| `<Space>c` | Code |
| `<Space>f` | Find |
| `<Space>s` | Search |
| `<Space>t` | Toggle |
| `<Space>h` | Git Hunk |
