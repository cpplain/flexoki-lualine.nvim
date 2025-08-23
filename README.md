# flexoki-lualine.nvim

A [lualine.nvim](https://github.com/nvim-lualine/lualine.nvim) theme integration for [flexoki.nvim](https://github.com/cpplain/flexoki.nvim), an inky color scheme for [Neovim](https://github.com/neovim/neovim). Based on [stephango.com/flexoki](https://stephango.com/flexoki).

## Features

- Supports all lualine modes with Flexoki colors
- Automatic light/dark theme switching
- Inactive window styling

## Installation

lazy.nvim

```lua
{
  "cpplain/flexoki.nvim",
  lazy = false,
  priority = 1000,
},
{
  "cpplain/flexoki-lualine.nvim",
  dependencies = { "cpplain/flexoki.nvim" },
}
```

## Usage

```lua
-- Load flexoki color scheme
require("flexoki").setup()
vim.cmd.colorscheme("flexoki")

-- Configure lualine theme
require("lualine").setup({
  options = {
    theme = "flexoki",
  },
})
```

The theme automatically adapts when switching between light and dark backgrounds with `vim.o.background`.

See [cpplain/flexoki.nvim](https://github.com/cpplain/flexoki.nvim) for complete color scheme documentation and configuration options.
