# nvim setup

This repo is meant to be stored inside `~/.config/nvim/` to configure neovim.

# Notable Changes from kickstarter nvim

## LSP additions

* clangd
* tsls
* `/lsp/gdscript.lua`: Taken from [here](https://simondalvai.org/blog/godot-neovim/).

## Macros

* `<space e>`: run `lua vim.diagnostic.open_float()` to open full error messages as floating text 
