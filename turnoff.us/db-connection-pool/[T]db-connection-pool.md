极客漫画：数据库链接池中的生生死死
===============

![Life (and Death) in the DB Connection Pool](http://turnoff.us/image/en/db-connection-pool.png)

- 数据库连接池用于增强在数据库上执行操作的性能。但是，在这种“池子”里面生存可是非常困难的。比如这位 Blick ，是一个连接对象……
- Hi！
- ……这是数据库连接池
- 你！来这里，到这个角落去执行： `SELECT 1 FROM DUAL`
- 干的不错！祝你好运（行）！
- 你，去那边！`SELECT 1 FROM DUAL`
- 老板，连接被拒绝啦！
- 厄该死，我痛恨这个工作！
- 下一个，kiddo，`SELECT 2 FROM DAUL`
- 试试……

--------

数据库连接池是常用的 B/S 技术，而似乎生活在这个“池子”里面的那些连接对象有点不幸。

要是顺利的话，你干完活就可以歇着了。

要是不顺利，比如你掌握的连接已经被拒绝了，那么……

你就会被“砰”地干掉。你怕不怕？（话说回来，回答错误会不会也被“砰”……）

----
via: http://turnoff.us/geek/db-connection-pool/

作者：[Daniel Stori][a]
译者&点评：[wxy](https://github.com/wxy)
校对：[校对者ID](https://github.com/校对者ID)
合成：[合成者ID](https://github.com/合成者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]:http://turnoff.us/about/
