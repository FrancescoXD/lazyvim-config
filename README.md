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

## Errors
When you open a python file if you get `Indentation contains tabs`, make a file in the root directory called `.flake8` and insert this:
```python
[flake8]
max-line-length = 99
ignore = W191
```

And that's all!

