极客漫画：谁杀死了 MySQL
===============

![who-killed-mysql](https://github.com/LCTT/comic/raw/master/turnoff.us/who-killed-mysql/who-killed-mysql.png)

- 此刻，在内核中……
- 怎么了，Apache，有访问请求了？
- 没多少，这几秒钟才 600 个请求而已。
- 啊！MySQL 死了！
- 让我看看没完成的事务。他是被 SIGKILL 杀死的!
- 事务
- 这能是谁干的呢？
- 我估计会有上千个 500 错误消息。让我们去看看日志是谁干的。
- 没戏：/var/log 被删除了！
- 你一个 Java 进程在我们灯塔国（LAMP Stack）干啥？
- 在证明我有罪前，我是清白了。此外，你是唯一一个以根权限运行的进程……
- 嗨，大家好，你们听说了 MySQL 那事了吗？
- 你来的正好，Ruby……你一直不喜欢 MySQL。我们都知道你爱上了 PostgreSQL。
- 警告：谁也不许离开这里。在这个 SIGKILL 案件里面你们都有嫌疑。
- 谁杀了 MySQL？
- Java：内存狂魔
- Apache：权限黑手
- PHP：自卑情节
- Ruby：勾结嫌疑
- 待续……

---

LAMP 架构，指 Linux + Apache + MySQL + PHP 组合构成的一个完整的 Web 服务架构。这是一个经典而有点过时的架构，适合于小型的 Web 服务。

在这里 MySQL 意外被 [SIGKILL](https://linux.cn/article-8791-1.html) [杀死](https://linux.cn/article-8771-1.html)了，没有留下任何遗言和痕迹（日志）。

---
via: http://turnoff.us/geek/who-killed-mysql/

作者：[Daniel Stori][a]
译者：[wxy](https://github.com/wxy)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]:http://turnoff.us/about/
