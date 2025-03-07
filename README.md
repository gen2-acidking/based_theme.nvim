# based-theme.nvim

A minimalist Neovim theme built with Lush.nvim.

## Installation

### Using Lazy.nvim  
Add the following to your `lazy.lua` configuration:  
```lua
return {
    'your-username/based-theme.nvim',
    dependencies = { 'rktjmp/lush.nvim' },
    priority = 1000, -- Load before other themes
    config = function()
        vim.cmd.colorscheme("based-theme")
    end
}
```

### Using Packer.nvim  
Add the following to your `packer.lua` configuration:  
```lua
use {
    'your-username/based-theme.nvim',
    requires = { 'rktjmp/lush.nvim' },
    config = function()
        vim.cmd.colorscheme("based-theme")
    end
}
```
After adding it, run:  
```
:PackerSync
```

### Using vim-plug  
Add the following to your `init.vim` or `init.lua`:  
```vim
Plug 'rktjmp/lush.nvim'
Plug 'your-username/based-theme.nvim'
```
After adding it, install with:  
```
:PlugInstall
```

Then load the theme:  
```
:colorscheme based-theme
```

## Usage  
Once installed, load the theme with:  
```
:colorscheme based-theme
```

## Features  
- Treesitter support  
- LSP highlights  
- Minimalist and fast  
- Works with Neovim 0.8+  

## License  
This theme is released under the MIT License.  
See LICENSE for details.

