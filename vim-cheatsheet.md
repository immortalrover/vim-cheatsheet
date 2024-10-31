# vim: set foldmethod=marker:

# Must know / 必知
normal:
- `zo` open fold / 打开折叠
- `zc` close fold / 关闭折叠

# vim basic operations / vim基础操作 {{{
normal:
- `h` go left / 向左移动一格
- `j` go down / 向下移动一格
- `k` go up / 向上移动一格
- `l` go right / 向右移动一格
- `zz` go to the middle of the view / 到视角中间
- `zt` go to the top of the view / 到视角顶端
- `zb` go to the bottom of the view / 到视角底端
- `<C-w> o` open current window / 打开当前的窗口
- `<C-w> c` close current window / 关闭当前的窗口
- `<C-w> w` change to next window / 切换到下一个窗口
- `<C-w> =` make all windows (almost) equally high and wide / 尽量让所有窗口同样高和宽
- `<C-w> <` decrease current window width by N (default 1). / 减少当前窗口的宽度
- `<C-w> >` increase current window width by N (default 1). / 增加当前窗口的宽度
- `<C-w> -` decrease current window height by N (default 1). / 减少当前窗口的高度
- `<C-w> +` increase current window height by N (default 1). / 增加当前窗口的高度
# }}}

# vim customization operations / vim魔改操作 {{{
normal:
- <space> start visual mode and select current word / 进入可视化模式并且选择当前单词
- <F1> open vim-cheatsheet.md / 打开vim备忘录
- <F2> visualize special words / 可视化不可见单词
- <C-q> highlight search answers / 高亮/取消高亮搜索结果

insert:
- <C-l> go right / 向右移动一格(能够移动到最后一格的右边)

visual:
- <space> forward to the end of word / 向后到单词的末尾(如果已经在末尾则到下一个单词末尾)
# }}}

# vim plugin cheatsheet / vim 插件备忘录 {{{
## vim-commentary 一个注释插件 {{{
normal:
- <C-/> commentary / 注释
## }}}

## vim-fugitive 一个git插件 {{{
command:
- :`G` open vim-fugitive / 打开vim-fugitive
    - `a` press "a" before your modified files / 在你修改的文件前按"a"键
    - `cc` press "cc" to create a commit / 按下"cc"去创建一个commit
- :`G push` git push / git推送远端 
    - `G push -u origin` git push to origin / git推送上游(新分支必备)
## }}}

## vimspector 一个调试窗口插件 {{{
normal:
- `\dd` start vimspector / 启动vimspector(一个调试窗口)
- `\dc` continue to test / 继续调试
- `\dT` clear breakpoints / 清除断点
- `\dk` restart vimspector / 重新启动vimspector
- `\de` exit vimspector / 退出vimspector
- <F5> continue to test / 继续调试
- <F9> toggle breakpoint / 切换断点状态(打/取消断点)
- <F10> step over / 单步调试
## }}}

## coc.nvim 一个补全插件 {{{
insert:
- `<TAB>` code completion / 代码补全(如果有补全选项的话)
- `<C-j>` jump next completion / 跳转到下一个代码补全
- `<C-k>` jump prev completion / 跳转到上一个代码补全
## }}}
# }}}
