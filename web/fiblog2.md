title:砍号重练的fiblog
tag:rest
date:0:58 2013/4/2

砍号重练的fiblog

刚做的fiblog我以前觉得挺好的说，

我甚至幼稚的以为fiblog可以用很久，可以去玩其他东西。

上次有网友提议开放它，我觉得只需写一下说明就行。

于是就动手啊。

+ 首先我发现必须要用到命令行，因为当成是模块的话，模块是给开发者使用的。不能让用户写代码。

+ 其次是发现我本来是用访问路径和启动脚本来分别完成blog同步和blog上传的

+ 用脚本启动当然也是上不了台面的做法。用路径访问？初衷是对的应该。但是需要验证权限。

+ 就为了这验证权限，不得不写个登录。。我了个大擦。总之我写了个登录模块，为了以后模块复用，做成完全可以跟程序分离的那种。

+ 我停下写博客，是因为发现之前太幼稚了，什么都说，什么都写。我虽然脸皮厚，不担心水平幼稚被人笑话。但是前天看了下js编码规范。我靠我以前写的真是一坨啊。连个JSLint都不用，也没有构建，文档生成啥的。格式更是大错特错。总之是很菜啦。等我开始略规范的编码，再提交代码好了。。

+ 既然不能直接用脚本和访问路径控制blog的一些操作。我决定索性做个控制面板好了。

+ 总之这个博客生成工具越来越不纯粹了。它已经不再仅仅是一个工具。

变得有点`庞大`起来，已经不是我这样的小菜鸟可以控制了。

不过我还是会非常仔细的做这个的，毕竟这是一个我自己大多数模块全部上战场的程序。

