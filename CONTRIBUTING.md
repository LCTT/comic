LCTT/comic 协作流程
==========

## 导航

- [1、选题](#1选题)
- [2、文字翻译并点评](#2文字翻译并点评)
- [3、图文合成](#3图文合成)
- [4、终校及发布](#4终校及发布)

---

## 1、选题

主要负责漫画源站更新的漫画同步转录为 Markdown 文件。

包括：

- A、抄录漫画中英文到 Markdown 中
- B、更新站点待翻译漫画列表
- C、更新站点已完成汉化漫画列表

规则：

- 选题只需要按照模版提供 Markdown 文件，其中包括漫画内的文字及漫画图片地址。
- 根据该漫画名称创建文件夹，一个或一系列漫画一个目录。
- 为了便于索引，将该漫画目录做符号链接到 `sources` 下。
- 放置路径要求：
	以站点 turnoff.us 为例，其中有这样一幅漫画地址为： http://turnoff.us/geek/the-depressed-developer/ 。
	
	那么选题的 Markdown 文件放置的路径 (`/` 表示 LCTT/comic 主仓库根目录) 为： `/turnoff.us/the-depressed-developer/the-depressed-developer.md`

	如果为该漫画一个系列，则为：`/turnoff.us/the-depressed-developer-series/the-depressed-developer-series.md`
- Markdown 选题文件相关格式参照 [select.txt](https://github.com/LCTT/comic/blob/master/select.txt)

---

## 2、文字翻译并点评

这一环节主要为贡献者参与环节。

主要负责站点待翻译漫画列表中列出的 Markdown 文件中的英文进行翻译。并根据根据漫画内容编写相应的点评、解释和扩展信息。

翻译力求 _信_、_达_、_雅_。

翻译完毕后，将该文件的符号链接移动至 `translated`，而不要移动该漫画目录 。

完成后，可以提交 PR。

---

## 3、图文合成

主要负责原图英文檫除、添加已校对的中文译文。

这一环节可以使用 Photoshop 或者 GIMP 等图像编辑软件来进行。

_注意：_

- a、添加右上角字体信息。典型的，我们采用的字体信息是：“字体： 蔡云汉天真娃娃书法字体，Comic Sans MS”，其中“蔡云汉天真娃娃书法字体”已取得字体作者授权。
- b、左下角如无底部原创作者，请添加（如 “Daniel Stori {turnoff.us}”）。
- c、右下角添加文字翻译、图文合成等信息，如都是一个人，可以写作“汉化：xxx”。
- d、输出 png8 图像，并拉到 [tinypng](https://tinypng.com/) 进行图像压缩。

图文合成完毕后，将该目录的符号链接移动至 `composited`，而不要移动该漫画目录 。

完成后，可以提交 PR。

---

## 4、终校及发布

主要负责进行最后的审核，然后发布到 [Linux.中国](https://linux.cn)。

发布后，将该目录的符号链接移动至 `published`，而不要移动该漫画目录 。

此环节由 [老王](https://github.com/wxy) 进行。

---
Fine.
