LCTT/comic 协作流程
==========

## 1、选题

主要负责漫画源站更新的漫画同步转录为 Markdown 文件。

包括：

- A、抄录漫画中英文到 Markdown 中
- B、更新站点待翻译漫画列表
- C、更新站点已完成汉化漫画列表

规则：

以站点 turnoff.us 为例，其中有这样一幅漫画地址为  http://turnoff.us/geek/the-depressed-developer/ 。

那么选题的 Markdown 文件放置的路径 (/ 表示 LCTT/comic 主仓库根目录) 为：

/turnoff.us/the-depressed-developer/the-depressed-developer.md

如果为该漫画一个系列，则为:

/turnoff.us/the-depressed-developer-series/the-depressed-developer-series.md

Markdown 选题文件相关格式参照 [select.txt](https://github.com/LCTT/comic/blob/master/select.txt)

## 2、文字翻译

这一环节主要为贡献者参与环节。

主要负责站点待翻译漫画列表中列出的 Markdown 文件中的英文进行翻译。

翻译力求 _信_、_达_、_雅_。

_注意：_

_翻译过程中，只需要添加中文译文，原英文内容不需要删除，保持原样即可。_

申领翻译时，文件名前缀改为 _[Translating]_。

翻译完毕后，文件名前缀改为 _[Translated]_。

## 3、校对

主要负责核对文字翻译是否遵循原意、是否表达清楚而无歧义、是否存在别字，如存在的，则进行修正。

申领校对时，文件名前缀改为 _[Proofing]_。

校对完毕后，文件名前缀改为 _[Proofed]_。

## 4、图文合成

主要负责原图英文檫除、添加已校对的中文译文。

这一环节可以使用 Photoshop 或者 GIMP 等图像编辑软件来进行。

_注意：_

- A、添加右上角字体信息。
- b、添加底部原创作者、文字翻译、图文合成等信息。
- C、输出 png 图像，并拉到 [tinypng](https://tinypng.com/) 进行图像压缩。

申领图文合成时，文件名前缀改为 _[Compositing]_。

图文合成完毕后，文件名前缀改为 _[Composited]_。

## 5、点评

主要负责根据漫画内容编写相应的技巧、心得的点评内容。

申领点评时，文件名前缀改为 _[Commenting]_。

点评完毕后，文件名前缀改为 _[Commented]_。

## 6、终校及发布

主要负责进行最后的审核，然后发布到 [Linux.中国](https://linux.cn)。
