# move.vim 
Syntax highlighting for the 2024 edition of Sui Move smart contract programming language.

### Installation

Install via your vim plugin manager of choice.

For `vim-plug` add to your `.vimrc`:

```vim
Plug 'Reblixt/move.vim', {'branch': 'sui-move'}
```
Then run `:PlugInstall`.

or if using Neovim with lazy package manager

Add this is your lazy configuration:
```lua 
return {
  "Reblixt/move.vim",
  event = "BufReadPre",
  lazy = false,
}
```

