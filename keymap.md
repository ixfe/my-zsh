/**
控制台快捷键
⌃ + u：清空当前行
⌃ + a：移动到行首
⌃ + e：移动到行尾
⌃ + f：向前移动
⌃ + b：向后移动
⌃ + p：上一条命令
⌃ + n：下一条命令
⌃ + r：搜索历史命令
⌃ + y：召回最近用命令删除的文字
⌃ + h：删除光标之前的字符
⌃ + d：删除光标所指的字符
⌃ + w：删除光标之前的单词
⌃ + k：删除从光标到行尾的内容
⌃ + t：交换光标和之前的字符
——————————————————————————————————
**/
/**
  option 为hammerspoon的功能键
  option + shift 为hammerspoon的扩展功能键

  cmd 为编辑器的控制键
  cmd + shift 为编辑器的扩展控制键
**/
/**

vim 相关

 // vim-easymotion#
  <leader><leader> w 像后移动 到单词开头
  <leader><leader> b 像前移动到单词开头
  <leader><leader> e 向后移动到单词结尾
  <leader><leader> ge 向前移动到单词结尾
  <leader><leader> l 向光标位置右后部分全局移动
  <leader><leader> h 向光标位置左上部分移动
  <leader><leader> j 向下移动到某一行开头
  <leader><leader> k 向上移动到某一行开头
  <leader><leader><leader> j 全局移动 `



   // t. 光标移动到.的位置
   // tx 光标移动到x的位置


   // c( 当前行光标处往前删除
   // c) 往后删除

  // 处理包裹的字符
    c s '"将'改为" 
    y s i w { 给一个单词加花括号
    y s i w <div>t 单词包裹标签
    d s " 删除字符周围的"
    可视化模式下使用选择范围 + S

    yiw 选中当前单词
    viwp 选中当前单词并替换为寄存器里的内容

  // 批量大小写
    gu + 范围 小写
    gU + 范围 大写
    gUU 整行大写
    guu 整行小写
    u + 范围 可视化模式下 小写
    U + 范围 可视化模式下大写
    ~ 大小写互换



  z + z 将当前行置于屏幕中央
  点（.） . 功能：重复上一次的修改
  
  v + a + I 选中当前整个函数
  v + a + i 选中当前整个函数（不包含最后一个括号）
  v + i + i 选中当前函数中的内容


  v 选中内容后，i，则在选中的内容进入多光标模式
    
  // 
    ctrl + f 向下移动一屏
    ctrl + b 向上移动一屏
    ctrl + d 向下滚动半屏
    ctrl + u 向上滚动半屏
    Ctrl + e 向下滚动一行
    ctrl + y 向上滚动一行
    zz 将当前行置于屏幕中央
    zt 将当前行置于屏幕顶部
    zb 将当前行置于屏幕底部
    gg 调到文件首
    G 调到文件尾
    
    g$ 行尾
    g^ 行首 


    gc 对选中的进行注释
    gcc 当前行注释

    行数 + gg/G 调到指定行

  // 折叠
        zfi{      # 折叠光标当前所在的大括号{里面的文本
        zfa{      # 折叠光标当前所在的大括号{里面的文本和大括号本身
        zfG       # 从当前光标所在行开始，折叠到文件尾
        zf10j     # 从当前光标所在行开始，继续向下折叠10行
        zfip      # 折叠内部段落

        za    # 切换(alternative)折叠状态,只能用在已折叠/未折叠的行
        zR    # 展开所有折叠
        zM    # 收缩所有折叠
  // 模式匹配
    先输入/ 进入命令模式
    \c	查找模式忽略大小写
    \C	查找模式强制区分大小写
**/


# 快捷键整理
---

-  C => ctrl
-  S => shift
-  A => alt
-  T => tab
-  O => option
-  ⌘ => commend
### 编辑器快捷键

> cmd+number(数字键),切换左侧控制 
 - ⌘ +1 



### MacOS快捷键

C + ⌘ + space 打开emoji

C + ⌘ + f 全屏


### Surfingkeys (chrome extend)

t 搜索书签/历史
ab 添加书签
: 执行js代码
