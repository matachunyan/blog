#1.简介
  Vim编辑器是功能强大的跨平台文本文件编辑工具，继承自Unix系统的Vi编辑器，支持Linux/Mac OS X/Windows系统，利用它可以建立、修改文本文件。
#2.进入vim
   我的电脑是WINDOWS系统
   安装nodejs?[下载地址](https://nodejs.org/zh-cn/)
    安装git?[下载地址](https://git-scm.com/downloads)
   桌面空白处右击Git Bash Here,可以
  
你也可在Git Bash Here,可以在终端输入下面的命令，获赠  vim 教程官方版
```



$ vimtutor

```




![3.png](http://upload-images.jianshu.io/upload_images/3016465-0ea8f11c4461db88.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
在终端输入下面的命令

```

$ vim [文件名]

```

![2.png](http://upload-images.jianshu.io/upload_images/3016465-a7f0b2a0466ec088.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
其中test是我自己定义文件的路径名。如果文件不存在，它将为你建立一个新文件。
下面进入test.txt中
![4.png](http://upload-images.jianshu.io/upload_images/3016465-36e3195a76d74b8c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#3.插入模式
在键盘上按下  i   ，进入插入模式，可以对文本进行编辑


![7.png](http://upload-images.jianshu.io/upload_images/3016465-95cc73e89597b33c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#4.命令模式
在键盘上按下  esc 键  ，进入命令模式

![6.png](http://upload-images.jianshu.io/upload_images/3016465-ac1b2a7009b78bc1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#5.简单命令
以下命令均在命令模式中输入
#####   基本命令
```


x→ 删当前光标所在的一个字符。
:wq?→ 存盘 + 退出 (:w?存盘,?:q?退出) ?
dd→ 删除当前行，并把删除的行存到剪贴板里
p→ 粘贴剪贴板
a → 在光标后插入
o → 在当前行后插入一个新行
O → 在当前行前插入一个新行
cw → 替换从光标所在位置后到一个单词结尾的字符
```
#####   移动光标

```
0 → 数字零，到行头
^ → 到本行第一个不是blank字符的位置（所谓blank字符就是空格，tab，换行，回车等）
$ → 到本行行尾
g_ → 到本行最后一个不是blank字符的位置。
/pattern → 搜索 pattern 的字符串
```
#####   复制粘贴
p/P都可以，p是表示在当前位置之后，P表示在当前位置之前
```
P→ 粘贴
yy?→ 拷贝当前行当行于?ddP
```
#####   字符串搜索
通过搜索该字符串到达指定行。如果希望进行正向搜索，将待搜索的字符串置于两个/
之间；如果希望反向搜索，则将字符串放在两个?之间。
```
:/str/ 正向搜索，将光标移到下一个包含字符串 str 的行
:?str? 反向搜索，将光标移到上一个包含字符串 str 的行
:/str/w file 正向搜索，并将第一个包含字符串 str 的行写入 file 文件
:/str1/,/str2/w file 正向搜索，并将包含字符串 str1 的行至包含字符串 str2 的行写

```

#####  指令图
![21.jpg](http://upload-images.jianshu.io/upload_images/3016465-3e0226ac18bdec01.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#6.结束语
vim还有许多便捷的命令
http://www.cnblogs.com/jiqingwu/archive/2012/06/14/vim_notes.html
vim还有许多强大的功能和插件提升效率
https://zhuanlan.zhihu.com/hack-vim
可以打造一个适合你自己的vim！