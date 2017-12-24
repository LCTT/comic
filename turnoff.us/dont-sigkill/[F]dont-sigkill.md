极客漫画：不要使用 SIGKILL 的原因（看哭了）
===============

![The Real Reason to Not Use SIGKILL](https://github.com/LCTT/comic/raw/master/turnoff.us/dont-sigkill/dont-sigkill.png)

- 这位是鲍勃，他是一个 Linux 进程。
- 嗨！大家好。
- 像其它进程一样，鲍勃有他的线程，他们与他生活在一个家里（context），充满回忆（memory），充满爱。
- 也像所有的进程一样，有时候难免他也会被干掉。
- 当我们使用温和的 SIGTERM 信号优雅地干掉一个进程时 …
- … 我们会给他一些时间，让他能和孩子们告个别，以便孩子们把手里的事情做完 …
- … 并与彼此告别。
- 这就是一个进程的一辈子！
- 而另外一种情况下，当我们残忍地用 SIGKILL 干掉一个进程时，他们根本没有机会结束工作并彼此道别 …
- … 这简直太可怜了！
- 爸爸！！！
- 所以，请不要使用 SIGKILL，给这些孩子们一个平静离开内核的机会吧。
- 对他们好点。
- 爸爸，我们要去哪里？
- 爸爸，你在哪里啊？

----

在 Linux 中，通常可以发送一些信号来杀死一个进程，一般用来杀死进程的信号有 SIGTERM、 SIGKILL。但是，如果希望进程合理地终止，就不要发送硬中断信号 SIGKILL，因为该信号是不能拦截的，进程接到该信号之后会马上退出，并没有机会进行现场清理——这包括对线程的关闭等操作。更好的做法是，发送 SIGTERM 信号，这样进程在接到该信号后，可以做一些退出的准备工作。

或许你之前对如何杀死进程并没有感到什么不同，但是，看了这幅漫画，你不觉得那些孩子们（线程）很可怜么——虽然 温和的 SIGTERM 也是要全家干掉的。哭~

----
via: http://turnoff.us/geek/dont-sigkill/

作者：[Daniel Stori][a]
译者&校对&点评：[wxy](https://github.com/wxy)
合成：[wxy](https://github.com/wxy)


本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]:http://turnoff.us/about/
