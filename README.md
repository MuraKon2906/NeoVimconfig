
# ✨ MuraKon's NeoFig Configuration ✨

Welcome to my Neovim configuration! This setup leverages the power of [lazy.nvim](https://github.com/folke/lazy.nvim) to manage plugins efficiently. Below, you'll find a detailed breakdown of the features and plugins used in this configuration. 🚀

## 📋 Features

- **Line Numbers**: Enabled by default to keep track of code lines easily.
- **Spaces over Tabs**: Configured to use spaces instead of tabs for better code consistency.
- **Custom Tab Width**: Set to 2 spaces for a more compact and readable code layout.
- **Leader Key**: Mapped to `<Space>` for quick access to custom keybindings.

## 🔌 Plugins
🚀 Features

## 🖌️ Aesthetic Theme - Catppuccin
Catppuccin Theme: A soothing and visually appealing color scheme to make your coding sessions enjoyable.
Configuration File: catppuccin.lua

## 📜 Status Line - Lualine
Lualine: A blazing-fast and easy-to-configure status line for Neovim, written in Lua.
Configuration File: lualine.lua

## 📁 File Explorer - Neo-tree
Neo-tree: A modern and highly customizable file explorer for Neovim.
Configuration File: neo-tree.lua

## 🔍 Fuzzy Finder - Telescope
Telescope: An extendable fuzzy finder over lists that brings together functionality like file searching, picking, and much more.
Configuration File: telescope.lua

## 🌲 Syntax Highlighting - Treesitter
Treesitter: Advanced syntax highlighting and code understanding using Neovim's Treesitter integration.
Configuration File: treesitter.lua
## 📂 File Structure
init.lua: Main configuration file that loads all the modules.
catppuccin.lua: Configuration for the Catppuccin theme.
lualine.lua: Configuration for the Lualine status line.
neo-tree.lua: Configuration for the Neo-tree file explorer.
telescope.lua: Configuration for the Telescope fuzzy finder.
treesitter.lua: Configuration for Treesitter.
vim-options.lua: General Vim options and settings.

## 🗝️ Keybindings

- **Find Files**: Use `<C-p>` to open the file finder.
- **Live Grep**: Use `<leader>fg` (default: `<Space>fg`) to search through your codebase.
- **File Explorer**: Use '<C-n>' ('<CTRL-n>')

## 🌈 Color Scheme

The default colorscheme is set to `catppuccin` for a delightful and refreshing look.

```lua
vim.cmd.colorscheme "catppuccin"
```
## More pluggins will be added !

---
