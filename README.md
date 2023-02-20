# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

## Changes
I've changed the `lua/config/options.lua` file adding these lines:
```lua
vim.opt.expandtab = false
vim.opt.tabstop = 4
vim.opt.shiftwidth = 4
```

Then I've installed with *Mason*:
- clangd
- clang-formatter

And that's all!

