极客漫画：最后一个问题
===============

![One Last Question](https://github.com/LCTT/comic/raw/master/turnoff.us/one-last-question/one-last-question.png)

- 很高兴，我们终于达成了保证世界和平的共识。
- 我也很高兴，但是我还有最后一个问题。你怎么查看你的进程？倒数三个数之后咱俩一起说。


---

`ps aux` 以及 `ps -elf` 都是查看进程的方式，分别来自于 BSD 风格（必须不带 `-`）和 UNIX 风格（必须带 `-`），这两种方式都有不少人用，此外除了这种可组合的单字母选项方式之外，还有以 `--` 开头的 GNU 选项方式。

这个漫画就是说使用这两种方式的人就像 vim 党和 Emacs 党一样，随时都可能爆发圣战（大误 。

**附录：**

`ps aux` 是最常用的 UNIX 风格选项组合，其中的 `a` 简单的说，表示所有关联到终端的进程，如果同时使用 `x` 则代表所有进程；`u` 表示列出进程的用户。

另外，可能是由于错用 `ps -aux` 的人太多，一些新的 `ps` 版本会在输入 `ps -aux` 时显示 `ps aux` 的结果，而不是 `ps -aux` 原本的意义：列出用户 `x` 所有的进程，如果没有则报错。

`ps -elf` 的 `-e` 代表列出所有进程，`-l` 代表长格式，`-f` 代表完整的格式，有时候也用 `-F` 代表超完整的格式，具体大家试试便知。 不过，不同操作系统（如 Linux、BSD）的 `ps` 的版本和参数有很大差异，具体还是要以自己的手册而定。

另外一句题外话，之所以 `aux` 和 `-elf` 这两种选项组合常用，是由于这个组合正好是易记、易读的英文单词（辅助、精灵），其组合后的用途也很有用。这种情况也出现在其它的常见命令中。


注：本漫画中原来用的是 `ps -eLF`，在某些版本上这个参数是成立的，但是，大部分情况下都使用的是 `ps -elf`，因此我们做了修改。 

---

via: http://turnoff.us/geek/one-last-question/

作者：[Daniel Stori][a]
译者：[name1e5s](https://github.com/name1e5s)
校对：[wxy](https://github.com/wxy)
合成：[name1e5s](https://github.com/name1e5s)
点评：[name1e5s](https://github.com/name1e5s)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]:http://turnoff.us/about/
