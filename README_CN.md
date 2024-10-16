# vim-cheatsheet
[English](./README.md) | 简体中文

这是一个自用的vim快捷键备忘录

# 快速概览

## vim原生操作

简单、迅速地介绍一下vim的一些比较陌生的原生操作有什么用

## vim魔改操作

个人对vim的一些魔改操作

# 安装方法

在`.vimrc`中配置`vim-plug`:
```vim
call plug#begin('~/.vim/plugged')
    Plug 'immortalrover/vim-cheatsheet', {'do': 'mv vim_cheatsheet.md ~/.vim/'}
call plug#end()
```

然后在你的`.vimrc`中添加一个快捷键打开这个文件`vim_cheatsheet.md`, 比如:
```vim
nnoremap <F1> :e ~/.vim/vim_cheatsheet.md
```
