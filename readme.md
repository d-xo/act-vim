# `act-vim`

syntax highlighting in vim for the [`act`](https://github.com/dapphub/klab/blob/master/acts.md) smart
contract specification language.

To install copy `act.vim` to :

- `$XDG_CONFIG_HOME/nvim/syntax/act.vim` for `neovim`
- `$HOME/.vim/syntax/act.vim` for `vim`

You also probably want to add the following to your `init.vim` / `.vimrc`:

```vimscript
" use act.vim to highlight the act filetype
au! Syntax act source act.vim

" highlight act in markdown fenced code blocks
let g:markdown_fenced_languages = ['act']
```
