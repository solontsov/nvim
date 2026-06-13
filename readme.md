# Neovim Cheat Sheet

## 🧭 Movement

| Sub-Category | Command | Description |
| :--- | :--- | :--- |
| **Basic** | `h` `j` `k` `l` | Move Left / Down / Up / Right |
| | `w` `b` `e` `ge` | Word Motions (Next start, Prev start, Next end, Prev end) |
| **Line Position** | `0` `^` `$` | Start of line / First non-blank char / End of line |
| | `gg` `G` | First Line / Last Line |
| | `zz` | Center the current line on screen |
| **Screen & Page** | `H` `M` `L` | Screen Top (High) / Middle / Bottom (Low) |
| | `Ctrl` + `y` / `e` | Scroll One Line Up / Down |
| | `Ctrl` + `u` / `d` | Half Page Up / Down |
| | `Ctrl` + `b` / `f` | Full Page Back / Forward |
| **Search** | `/` `?` | Search Forward / Backward |
| | `n` `N` | Next Result / Previous Result |
| | `*` `#` | Search Current Word Forward / Backward |

## ✍️ Edit Mode

| Sub-Category | Command | Description |
| :--- | :--- | :--- |
| **Insert New Lines** | `o` | Insert New Line Below |
| | `O` | Insert New Line Above |
| **Insert At Line Start** | `I` | Insert at first non-blank character of line |
| **➡️ Indent** | `>>` |  |
| **⬅️ Unindent** | `<<` |  |
| | Ctrl-d | in insert mode |
| **🎨 Visual Mode** | `v` `V` | Visual Char Mode / Visual Line Mode |
| | `Ctrl`+`v` | Visual Block Mode |
| | `y` `d` `c` | Yank / Delete / Change current selection |
| **⚡ Autocomplete | Ctrl-n / Ctrl-p | next / previous completion |

## Actions

| Sub-Category | Command | Description |
| :--- | :--- | :--- |
| **✂️ Delete / Cut** | `x` `X` | Delete Character (under cursor / before cursor) |
| | `dw` `de` `db` | Delete Word motions |
| | `dd` `Ndd` | Delete Line / Delete N Lines |
| | `D` `d0` | Delete to End of line / Start of line |
| | `diw` `daw` | Delete inside/around word (Text Objects) |
| **📋 Copy / Yank** | `yy` `Y` | Yank Line |
| | `yw` | Yank Word |
| | `yiw` `yaw` | Yank inside/around word (Text Objects) |
| | `"ay` | Yank current selection into Register 'a' |
| **📋 Paste** | `p` `P` | Paste Below / Above |
| | `"ap` | Paste from Register 'a' |
| | `"+p` | Paste from clipboard |
| **↩️ Undo** | `u` |  |
| | Ctrl-u | 

## 🌐 Lua

| Sub-Category | Command | Description |
| :--- | :--- | :--- |
| **Help** | `:help lua-guide` | Lua guide and reference |

## 🎥 Macros

| Sub-Category | Command | Description |
| :--- | :--- | :--- |
| **🔴 Recording** | `q{register}` | Start recording macro into register (use any letter/number) |
| **⏹️ Stop** | `q` | Stop recording |
| **▶️ Play** | `@{register}` | Run recorded macro |

## 📄 Multi buffers

| Sub-Category | Command | Description |
| :--- | :--- | :--- |
| **List buffers** | `:buffers` / `:ls` | Show all open buffers |
| **New buffer** | `:enew` | Create a new empty buffer |
| **Select buffer** | `:bnext` / `:bprevious` | Move to next/previous buffer |
| **Close buffer** | `:bdelete` | Close current buffer |

---
## 📚 Other cheat sheets
 [https://github.com/gibbok/vim-cheat-sheet](https://github.com/gibbok/vim-cheat-sheet).
