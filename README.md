
# ✨ MuraKon's NeoFig Configuration ✨

Welcome to my Neovim configuration! This setup leverages the power of [lazy.nvim](https://github.com/folke/lazy.nvim) to manage plugins efficiently. Below, you'll find a detailed breakdown of the features and plugins used in this configuration. 🚀

## 📋 Features

- **Line Numbers**: Enabled by default to keep track of code lines easily.
- **Spaces over Tabs**: Configured to use spaces instead of tabs for better code consistency.
- **Custom Tab Width**: Set to 2 spaces for a more compact and readable code layout.
- **Leader Key**: Mapped to `<Space>` for quick access to custom keybindings.

## 🔌 Plugins

### 🌟 [catppuccin/nvim](https://github.com/catppuccin/nvim)
A soothing color scheme inspired by the Catppuccin palette. It's set as the default colorscheme to provide a visually pleasing coding experience.

### 🔭 [nvim-telescope/telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
A highly extendable fuzzy finder over lists to quickly navigate files, live grep, and more.
- **Dependencies**: Requires `nvim-lua/plenary.nvim` for additional functionality.

### 🌳 [nvim-treesitter/nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
A tool to provide better syntax highlighting and code understanding using Treesitter.
- **Auto-updates**: Automatically keeps Treesitter parsers up-to-date with `:TSUpdate`.
- **Languages Supported**: Ensures installation of various language parsers like C, Lua, Vim, Elixir, JavaScript, HTML, Python, C++, Rust, and more.

## 🗝️ Keybindings

- **Find Files**: Use `<C-p>` to open the file finder.
- **Live Grep**: Use `<leader>fg` (default: `<Space>fg`) to search through your codebase.

## 🌈 Color Scheme

The default colorscheme is set to `catppuccin` for a delightful and refreshing look.

```lua
vim.cmd.colorscheme "catppuccin"
```

## 🎉 Enjoy Coding!

Feel free to customize further to suit your needs. Happy coding! ✨

---
