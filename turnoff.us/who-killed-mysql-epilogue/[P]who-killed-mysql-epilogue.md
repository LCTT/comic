谁杀死了 MySQL? - 后记
===============

![Who Killed MySQL? - Epilogue](https://github.com/LCTT/comic/raw/master/turnoff.us/who-killed-mysql-epilogue/who-killed-mysql-epilogue.png)

- 今天，一个进程在这里被杀死了。
- 死者是 MySQL，死因是 SIGKILL。
- 主要的嫌疑人是：
- Java、Apache、Ruby 和 PHP。
- 但是在用户层，发生了一些奇怪的事情……
- 谁杀死了 MYSQL - 后记
- John，我不太清楚，这些人看起来不像是罪犯。
- 我感觉不大妙。
- 内核警察
- 不要啊！这管道（PIPE）是干啥的！你们要把我带到哪儿？
- 指挥部， 439 号进程怎么了？
- 太糟糕了！Java 也被杀死了！先是 MySQL，现在又是 Java！
- Java、MySQL ... 等一下! 我们有已登录用户的照片吗?
- 指挥部，把已登录用户的照片发到 14 号终端。
- 嘿！这家伙不是来自甲骨……
- 就是他！和我怀疑的一样。
- 让我们剥夺他的权限，终止这场屠杀。
- 之后……
- 我觉得我们欠你一个道歉。
- 没事，给我点资源（ulimit），我去干活了！
- 现在，让我们注意新用户试图做的事情……
- 新用户警告
- 斯蒂芬·巴尔默
- 嘿，谁在这里说 Windows 的坏话呢？

这篇漫画意在讽刺 Oracle 收购太阳微系统公司之后，对收购来的资产一个个杀死，比如 MySQL，导致大多数发行版已经不使用 MySQL ，转向它的分支 MariaDB，在此之后，Oracle 还放弃了“不赚钱的” JavaEE。

然后之后，是以对开源不友善而著名的微软前总裁巴尔默——虽然现在新总裁纳德拉上台之后，微软公司乃至巴尔默都对开源的态度发生了一百八十度大转弯。

本篇漫画中涉及的一些技术方面的隐喻有：

- SIGKILL，是一种 UNIX/Posix 信号，用于结束一个进程，不可捕获。关于 SIGKILL ，可以看看[这篇漫画](https://linux.cn/article-8791-1.html)。
- PIPE，是 UNIX/Posix 中的一种进程通讯机制，数据可以通过管道进行传输，进行进程间通讯。此处引申为一个管道、通道，从漫画中可以看到， Java 439 进程感觉不妙的时候，其脚下已经有些塌陷的痕迹，而接着变成了一个通道——然后它就掉进去死了。
- ulimit，是 UNIX/Linux 中用于限制资源分配的命令，可以设置系统可以分配的文件句柄数等，像 Apache 之类的服务需要足够的句柄数才能提供更高的连接数。此处，头上顶着羽毛的 Apache 表示，它要占用一些 ulimit 分配的资源（去工作了）。

---
via: http://turnoff.us/geek/who-killed-mysql-epilogue/

作者：[Daniel Stori][a]
译者&点评：[ItsLucas](https://github.com/ItsLucas)
校对&合成：[wxy](https://github.com/wxy)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]:http://turnoff.us/about/
