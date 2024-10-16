# vim-cheatsheet
English | [简体中文](./README_CN.md)

This is a repository for personal Vim shortcut keys.

# Quick OverView

## Native Vim operations

Briefly and quickly introduce some lesser-known native Vim operations and their uses.

## Vim customization operations

Personal customizations for Vim operations

# Installation

Configure `vim-plug` in `.vimrc`:
```vim
call plug#begin('~/.vim/plugged')
    Plug 'immortalrover/vim-cheatsheet'
call plug#end()
```

Then, in your `.vimrc`, add a shortcut key to open the `vim-cheatsheet.md` file, for example:
```vim
nnoremap <F1> :e ~/.vim/plugged/vim-cheatsheet/vim-cheatsheet.md
```
