# Cnthon-Computer-Language
基于Python的沙雕中文新语言。。。
高级计算机编程语言：Cnthon
关于
简介
这其实是我的一个创意引发的，但是本来没有此意， 至于为什么，具体请看下表：

我的输入法经常要在中文和英语之间切换
懒得敲键盘的shift
常常错在细节上
一怒之下，我用闲暇时间开发了Cnthon。

这个项目采用了最先进的TDD(TreeNewBee-Driven Development)开发方式。

Cnthon一般含有三个文件：gcn.exe,Cnthon.exe和README.md

gcn：cn脚本编译器

Cnthon:Cnthon交互式环境

README：我变更了哪些内容

本人没有那么多时间与精力去编写IDE，所以先凑和着用吧...

咳咳，继续

具体实现就是Python里的exec，Python之父；这种函数都想得出，大佬啊...

首先定义一个列表，里面是未经改变的Python函数和保留关键字。之后replace掉中文，换上Python原生函数和保留关键字，再用exec编译...

很无聊，但是有时间会尝试用C实现一门真正的语言...

路人甲：别在这吹牛逼了，你C才刚刚开始学...

咳咳，路人甲已经被干掉了。就算不能用C，JetBrains的MPS也是可以的...

Cnthon的用法
和Python一样，有部分很多东西没有加入，比如库，该咋写还咋写。

Cnthon的特性
简洁，高效，方便，来自Python，对天朝子民友好

注意：不能使用记事本来当成IDE！文件编码保存为UTF-8！切记！
关于为什么不用字典实现
很简单，心血来潮，没有想优化，下次再优化吧...

变化的关键字一览
所有的变化 = [ "唠嗑", "找茬", "轮回", "抄家", "降维", "升维", "踢出", "找来", "打开", "执行", "虚无", "并且", "一旦", "不然", "否则", "干掉", "遛", "就是", "或者", "尝试", "错执", "从", "跳过", "匿名", "正确", "错误", "跳出","自个", "当", "定义", "生成", "不是", "在", "新类", ]

原本所有的 = [ "print", "input", "range", "len", "int","str", "return", "import", "open", "exec", "None", "and", "if", "elif", "else", "del", "for", "is", "or", "try", "except", "from", "continue", "lambda", "True", "False", "break","self", "while", "def", "yield", "not", "in","class", ]
