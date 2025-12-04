# Neovim Keyboard Shortcuts Cheatsheet

## 🟢 General & Window Management

| Key | Description | Mode |
| :--- | :--- | :--- |
| `<Space>` | **Leader Key** | Normal |
| `<C-s>` | Save file | Normal |
| `<leader>sn` | Save without auto-formatting | Normal |
| `<C-q>` | Quit file | Normal |
| `<leader>v` | Split window vertically | Normal |
| `<leader>h` | Split window horizontally | Normal |
| `<leader>se` | Equalize split sizes | Normal |
| `<leader>xs` | Close current split | Normal |
| `<C-h/j/k/l>` | Navigate splits (Left/Down/Up/Right) | Normal |
| `<leader>to` | Open new tab | Normal |
| `<leader>tx` | Close current tab | Normal |
| `<leader>tn` | Next tab | Normal |
| `<leader>tp` | Previous tab | Normal |
| `<leader>lw` | Toggle line wrapping | Normal |

## 📁 File Explorer (Neo-tree)

| Key | Description | Mode |
| :--- | :--- | :--- |
| `<leader>e` | Toggle File Explorer | Normal |
| `\` | Reveal current file in Explorer | Normal |
| `<leader>ngs`| Open Git Status window | Normal |
| **Inside Neo-tree:** | | |
| `l`, `<CR>` | Open file / Expand directory | Normal |
| `s` | Open in vertical split | Normal |
| `S` | Open in horizontal split | Normal |
| `t` | Open in new tab | Normal |
| `a` | Create file (end with `/` for dir) | Normal |
| `d` | Delete file/dir | Normal |
| `r` | Rename file/dir | Normal |
| `c` | Copy file | Normal |
| `m` | Move file | Normal |
| `?` | Show help | Normal |

## 🔍 Search & Fuzzy Finding (Telescope)

| Key | Description | Mode |
| :--- | :--- | :--- |
| `<leader>sf` | Find Files | Normal |
| `<leader>sg` | Live Grep (Search text) | Normal |
| `<leader>sw` | Search current word under cursor | Normal |
| `<leader>s.` | Search Recent Files | Normal |
| `<leader><leader>`| Find existing buffers | Normal |
| `<leader>/` | Fuzzily search in current buffer | Normal |
| `<leader>s/` | Grep in open files | Normal |
| `<leader>sd` | Search Diagnostics | Normal |
| `<leader>sk` | Search Keymaps | Normal |
| `<leader>sh` | Search Help | Normal |
| `<leader>sr` | Resume last search | Normal |

## 🧠 LSP & Coding

| Key | Description | Mode |
| :--- | :--- | :--- |
| `gd` | Goto Definition | Normal |
| `gr` | Goto References | Normal |
| `gI` | Goto Implementation | Normal |
| `gD` | Goto Declaration | Normal |
| `<leader>D` | Type Definition | Normal |
| `<leader>rn` | Rename symbol | Normal |
| `<leader>ca` | Code Action | Normal/Visual |
| `<leader>ds` | Document Symbols | Normal |
| `<leader>ws` | Workspace Symbols | Normal |
| `<leader>th` | Toggle Inlay Hints | Normal |
| `K` | Hover Documentation (Default) | Normal |
| `[d` | Previous Diagnostic | Normal |
| `]d` | Next Diagnostic | Normal |
| `<leader>d` | Open floating diagnostic | Normal |
| `<leader>q` | Open diagnostics list | Normal |

## 🤖 AI Generation (gen.nvim)

> **Note:** Trigger via command `:Gen` (select text in visual mode for context)

| Key | Description | Mode |
| :--- | :--- | :--- |
| `q` | Close response window | Normal (in Gen window) |
| `<C-r>` | Re-send current prompt | Normal (in Gen window) |
| `<C-cr>` | Accept/Replace selection | Normal (in Gen window) |

## ⌨️ Editing & Autocompletion

| Key | Description | Mode |
| :--- | :--- | :--- |
| `<C-Space>` | Trigger Completion | Insert |
| `<C-n>` / `<C-p>`| Next / Previous item | Insert |
| `<Tab>` / `<S-Tab>` | Next / Prev item (or Snippet Jump) | Insert |
| `<C-y>` | Confirm Completion | Insert |
| `<C-l>` | Snippet Jump Forward | Insert |
| `<C-h>` | Snippet Jump Backward | Insert |
| `<C-_>` / `<C-/>`| Toggle Comment | Normal/Visual |
| `x` | Delete char without yanking | Normal |
| `<` / `>` | Indent/Outdent (stays in visual) | Visual |
| `p` | Paste without overwriting register | Visual |

## 📄 Buffers & Navigation

| Key | Description | Mode |
| :--- | :--- | :--- |
| `<Tab>` | Next Buffer | Normal |
| `<S-Tab>` | Previous Buffer | Normal |
| `<leader>x` | Close Buffer | Normal |
| `<leader>b` | New Buffer | Normal |
| `<C-d>` | Scroll Down & Center | Normal |
| `<C-u>` | Scroll Up & Center | Normal |
| `n` | Next Search Result & Center | Normal |
| `N` | Previous Search Result & Center | Normal |
