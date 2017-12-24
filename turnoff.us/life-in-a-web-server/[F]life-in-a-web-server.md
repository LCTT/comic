极客漫画：Web 服务器中的生活
===============

![Life in a Web Server](https://github.com/LCTT/comic/raw/master/turnoff.us/life-in-a-web-server/life-in-a-web-server.png)

- 嗨，Coy，幸好你还没下班！
- 你能帮我处理这个请求吗？
- 我们从来不下班，不过，Dan，你的请求要等等才行，因为……
- ……现在我们所有的 http 线程都真的很忙！
- 嗨，Coy，那个家伙似乎不忙。
- 别急哥们，他被数据库操作挡住了，他啥都干不了。
- 伙计们！别为那个锁打架！不好意思 Dan，有时候就这样。
- Dan，你运气真好，15 号正在处理一个堆栈溢出，我会让他在回到池子前先处理你的请求。
- 啊啊啊，我需要更多堆栈，Coy！
- 噢，这不是你的错，那是破代码的问题。处理下这个，好嘛？
- Dan，这是你的页面和你的免费饼干。下次你可以带着这个饼干的牌子来，我们就会处理得更快些。
- 谢了， Coy。
- 我喜欢这地方。

----

Web 服务器总是忙忙碌碌的，从不下班，这似乎比运维工程师还要辛苦。 

每一个线程都在忙着，然而也有不太一样的，比如那个被数据库操作拖在那里的，就只能发呆；而那个被糟糕的代码搞得堆栈溢出的，看起来已经要崩溃了。

处理完请求之后，Web 服务器会给出生成的页面和 Cookie（饼干），如果下次带着这些饼干的编号来，那就可以很快地找到你要的饼干——这就是用饼干保存的会话。

这就是 Tomcat Web 服务器里面的生活。

----
via: http://turnoff.us/geek/life-in-a-web-server/

作者：[Daniel Stori][a]
译者：[wxy](https://github.com/wxy)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]:http://turnoff.us/about/
