HTML帮助文件的一般说明和约定
==============================================================

-使用指向Double Commander帮助外部内容的链接时，使用target="_blank"将目标设置为新窗口，如下例所示:
  <a title="Double Commander Home Page" href="https://doublecmd.sourceforge.io/" target="_blank">Homepage</a>
  
-为了与用户更友好，使我们与用户处于同一水平，我们用“我们”而不是“你”来交谈。
用户会觉得我们在一起工作。
(根据传统，除 “2.1. 基础帮助”，“2.2. 配置” 和 “2.3. 键盘布局” 外的所有章节。)

-不要在HTML文件名中使用点号。
只需根据它描述的内容命名文件，并假设我们不会重命名它。
即使今天的“findfiles.html”有了point 2.5，也不意味着它会一直是2.5。
但它永远都在谈论寻找文件。
保持引用指向“findfiles.html”将始终为真...
...举例来说，如果我们指向类似“sec2_5_findfiles.html”的内容，就不会出现这种情况。
将文本的章节号放在页面内，不要放在链接内。

-如果您想添加FAQ的链接，请不要使用问题编号，因为将来可能会更改。

-如果您想要添加当前仅在alpha版本(开发版本)或beta版本(通常是新主版本的第一个版本)中可用的特性的描述，则添加特殊标签:
  <span class="versionref"><sup>(Alpha version)</sup></span>
或者
  <span class="versionref"><sup>(Beta version)</sup></span>
发布后别忘了删除。


贡献者
============
  Alexander Koblov aka Alexx2000 (alexx2000@mail.ru)
  Denis Bisson (denis.bisson@denisbisson.org)
  Dmitry Kolomiets aka B4rr4cuda (B4rr4cuda@rambler.ru)
  Przemysław Nagay aka cobines (cobines@gmail.com)
  RedSkotina
  Rod J (rodmac_shiels@hotmail.com)
  Rustem Rakhimov (dok_rust@bk.ru)
  Sash0k
  Максим aka Ma$terok