# helix-config

**helix better vim**

My simple [Helix](https://helix-editor.com/) config. 
> Lines in total: 68 (59)

---

## 🎨 Theme

| Setting | Value |
|---|---|
| Theme | `gruvbox` |
| Mouse | disabled |
| Line numbers | `relative` |
| Default yank register | `+` (system clipboard) |
| LSP messages | shown |
| Cursor shape — insert | `bar` |
| Cursor shape — normal | `block` |
| Cursor shape — select | `underline` |

---

## ⌨️ Keybindings

### Navigation

| Key | Action |
|---|---|
| `}` | next paragraph |
| `{` | previous paragraph |
| `A-h` | previous buffer |
| `A-l` | next buffer |
| `A-w` | close buffer |

### Editing

| Key | Action |
|---|---|
| `Esc` | collapse selection, keep primary |
| `Ret` | smart Enter — move down + first non-whitespace |
| `A-Ret` | smart Enter — move up + first non-whitespace |
| `C-j` | move line down |
| `C-k` | move line up |
| `X` | extend line selection up |

### Git (prefix `A-g`)

| Key | Action |
|---|---|
| `A-g b` | `git blame` current line |
| `A-g s` | `git status --porcelain` |
| `A-g l` | last 10 commits for current file |
| `A-g B` | current branch |
| `A-g S` | full `git status` |

### Config

| Key | Action |
|---|---|
| `A-r` | reload config + buffer |
| `A-c` | open `config.toml` |

---

## 🚀 Install

```bash
git clone https://github.com/<your-name>/helix-config.git ~/.config/helix
```
Or just copy `config.toml` to `~/.config/helix/config.toml`.

---
