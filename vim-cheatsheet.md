# vim: set foldmethod=marker:

# vim basic operation / vim基础操作 {{{
normal:
- h go left / 向左移动一格
- j go down / 向下移动一格
- k go up / 向上移动一格
- l go right / 向右移动一格
# }}}

# vim customization operations / vim魔改操作 {{{
global:
- <C-/> commentary / 注释
normal:
- <space> start visual mode and select current word / 进入可视化模式并且选择当前单词
- <F1> open vim-cheatsheet.md / 打开vim备忘录
- <F2> visualize special words / 可视化不可见单词
insert:
- <C-l> go right / 向右移动一格(能够移动到最后一格的右边)
visual:
- <space> forward to the end of word / 向后到单词的末尾(如果已经在末尾则到下一个单词末尾)
# }}}

# vim plugin operation / vim插件操作 {{{
normal:
- \dd start vimspector / 启动vimspector(一个调试窗口)
- \dc continue to test / 继续调试
- \dT clear breakpoints / 清除断点
- \dk restart vimspector / 重新启动vimspector
- \de exit vimspector / 退出vimspector
- <F5> continue to test / 继续调试
- <F9> toggle breakpoint / 切换断点状态(打/取消断点)
- <F10> step over / 单步调试
    

# }}}
