---
url: https://mp.weixin.qq.com/s/JER462B3dVYlwVYl6rTmzw
title: "Skills的最正确用法，是将整个Github压缩成你自己的超级技能库。"
description: "开源的历史，就是最美的赞歌"
author: "数字生命卡兹克"
coverImage: "https://mmbiz.qpic.cn/mmbiz_jpg/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBMC46LJItAg8fftuuOM2ARCfhsiblXHGC030orXqPLwQUysYMKJKkkDw/0?wx_fmt=jpeg"
captured_at: "2026-03-08T06:24:37.938Z"
---

# Skills的最正确用法，是将整个Github压缩成你自己的超级技能库。

原创 数字生命卡兹克 *2026年1月21日 10:16*

昨天写了一篇关于在 [扣子上使用Skills的文章](https://mp.weixin.qq.com/s?__biz=MzIyMzA5NjEyMA==&mid=2647679068&idx=1&sn=6b3ae5770982ec685d57fe8a006e6317&scene=21#wechat_redirect) 。

里面用的案例，特别简单，就是把Github上一个非常经典的开源项目，封装成一个Skill，方便我们以后进行调用。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURrCo6BdbjkzCLanc3Qic2MdgRBhOrNZ15X8jMo0rx3z7t5hzp8XS4x2LIt8yMicVYJ7W0ylPGdRKiazg/640?wx_fmt=png&from=appmsg&wxfrom=5&wx_lazy=1&tp=webp#imgIndex=6)

这么做的原因特别简单，就是我一直觉得，重复造轮子是一件特别呆逼的事情，互联网三十年，开源世界大神这么多，其实你能想象到的绝大多数需求，都有大佬和真神们，在前方铺路，做出了现成的产品，然后开源了出来，给非常非常多的人用。

其实现在非常非常多的一些商业APP，特别是一些所谓的格式工厂、压缩之类的，绝大多数都是把一些大佬的开源工具，做个前端，给大家用。

之前我觉得没啥问题，确实，Github上面很多的开源项目，都是没有GUI的，全部需要部署，部署以后还是用命令行操作，真的，光环境这一条，就能卡死绝大多数的普通用户。

我自己，之前就是被挡在门外的普通用户。

有太多太多好玩的、实用的、很屌的开源项目，我用不了了。

比如格式转化这破事，没有AI之前，我每次就是去Google搜，MP3转WAV...

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBQbsK0pm13hkDic3ickPoznYY3BQyXLdTrxjKo4dvAhzNWqpKunibbh9VQ/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1#imgIndex=1)

然后就看着各种各样你也不知道是不是有刺客的链接，在向你招手。。。

所以，Skills一来，从文件结构上，它是可以把脚本和Prompt打包在一起的，这一点，跟单Prompt或者脚本完全不一样，再加上现在一些Coding能力强的基模和Agent，我觉得，它天然的擅长把很多的大佬们的开源项目Skill化，从而在Agent里面，为我所用。

而且你要相信那些历史悠久的经典开源项目，经历了无数的时间和使用者的鞭打，不管是成功率还是稳定性还是效率，都远超绝大多数的你根据需求，让AI临时去写的一些代码...

所以就搞了这么个东西，其实不止Coze，当你在OpenCode或者Claude Code这种支持Skills的产品里，只要你装了那个Claude官方那个能生成Skills的Skill，也就是skill-creator，打包Github上的开源项目，也是完全没问题的。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujEh5p3NjnQ57wJCbyeESFt4KeYlX7IQb7wVavRZTFntQptllViagXpeA/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1#imgIndex=23)

这种方式，就能最快速度，越过所谓的本地整合包，变成一个类似于Agent的产物，让你能快速的用上。

比如昨天扣子文章中，我把视频处理的开源项目FFmpeg和图片视频处理项目ImageMagick，封装成了一个多模态素材处理的Skill，它大概就是这个效果。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURrCo6BdbjkzCLanc3Qic2MdgD00PrEkiapfuEr2hicQ3KGaLHLTaRAUsIrVgScohfFUK27Ty0NqJozHg/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1#imgIndex=18)

然后呢，在文章中一个有趣的评论，引起了我的注意。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBNiagHkKiaeQyuj1jBp9IL1Ien58pnuJykMRicbbjgJCB3GjdFPNDVXbhg/640?wx_fmt=png&from=appmsg#imgIndex=4)

这个评论的问题没啥毛病，因为github上那么多开源项目，离大众肯定还是非常的遥远，我因为知道有特定的项目可以去处理特定的事，所以封装成Skill就特别的简单，但是大多数的普通人，可能连github是什么都不知道，那怎么封装呢？

这确实是个问题。

我当时想了两分钟，然后我一寻思，不对啊，这不都有AI了吗...

于是，我就回了一句：

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gB4lgGjlbfAQEd8KzazYZ3OtaAdSFsjyQ8NclRfrfvrAAAnv2h0Lu8NQ/640?wx_fmt=png&from=appmsg#imgIndex=5)

没想到，引起了好几个朋友非常正向的反馈。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBlgzWic3hvv9xcKxghARcwlOHicsr7BCQN8kVJE9mvIeHVDttgwZGjaiaw/640?wx_fmt=png&from=appmsg#imgIndex=6)

这个时候，我才意识到，其实，我的很多的小技巧，对于蛮多人来说，还是挺有价值的。

所以这块，我觉得我觉得可以单独拎一篇文章，来给大家讲一讲，普通人怎么把整个github，当成自己的弹药库，做成skill，让自己真正的，变得三头六臂无所不能。

比如，我自己现在，就已经封装了很多的skills。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBNqFv9hZJR4A36xRVMzC41Ofia9nUvkVbTez7NDkvnaX4WHMiahSaMn1g/640?wx_fmt=png&from=appmsg#imgIndex=7)

哦这个管理skills的skill，也是我自己建的一个skill，要不然感觉每次进到文件里看太麻烦了，我就可以直接用这个skill，对我本地的所有skill进行卸载删除修改优化操作...

举一个例子。

我相信大家经常都有一个需求，就是去各种视频网站上，下载视频，比如Youtube、B站等等。

我自己也有。

那我们就可以直接打开ChatGPT，选中GPT-5.2 Thinking（目前我认为搜索能力最好、幻觉程度最低的模型），当然，你用别的也行，一般来说问题都不大。

然后直接提出你的问题：

有没有那种就是去各种视频网站上，下载视频，比如Youtube、B站等等的github上的开源项目。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBBNK104uSicBIgOYXGO7FRgJJzKvpveLpvB4que5sEp62h7lWZF4TOQg/640?wx_fmt=png&from=appmsg#imgIndex=8)

在GPT搜索了一阵子以后，就会给你推荐一个，在github上，几乎封神的项目。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBe4e9HDf7cCTjG7VfBNZkYicnUeAcVTHttDU4ybkp2CNCb3TsZwzoZRw/640?wx_fmt=png&from=appmsg#imgIndex=9)

它叫做，yt-dlp。

github上143k的star，说是真神，也不为过。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gB8PHFbj2ia4HAHPnBGosSEQl5c0CkZLfTyuesTV6VgCic86QOpaWxOE5Q/640?wx_fmt=png&from=appmsg#imgIndex=10)

支持上千个网站。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBia27HN40q0FyCQPaXGH6eUua4PuGHaeczEAxWWxO4kLcB5LUuoG2ibuA/640?wx_fmt=png&from=appmsg#imgIndex=11)

这，就是yt-dlp，我觉得最伟大的项目之一。

你要相信，在这个世界上，在这个互联网上，有无数的大神和前人，已经为你铺好了前路。

你要相信，你的需求，永远不是这个世界上第一个提出这个需求的人，也绝对不是最后一个。

你要相信，人类在这几十年所积攒的历史，几乎覆盖了世界所有的领域，互联网，永远都是那个最深、最广的宝藏。

你要相信，在这一刻，你搜出来这个开源项目的这一刻，这就是人类开源精神的涓涓长河，在你面前展开的绝美的画卷。

我时常赞美这世界上，每一个愿意开源、每一个无私的将自己的知识分享出来的前辈们，正是因为他们，才让我们，能站在他们的肩上，去摘更美的星辰。

我们直接复制yt-dlp的github链接。

然后把这段Promtp发给你装好了skill-creator的OpenCode或者Claude Code：

帮我把这个开源工具https://github.com/yt-dlp/yt-dlp打包成一个Skill，只要我后续给出视频链接，就可以帮我下载视频。

这块如果还不懂或者不知道的skill-creator是啥的，可以去看我之前的那篇文章：

[一文带你看懂，火爆全网的Skills到底是个啥。](https://mp.weixin.qq.com/s?__biz=MzIyMzA5NjEyMA==&mid=2647678672&idx=1&sn=c3510896d2de19b5c5ab6805c27182e5&scene=21#wechat_redirect)

一般我的做法对打包，是先让Agent进行规划，然后再去写整个的Skill，这样我自己感觉，成功率会高一点、后期稳定性也会更强一点。

相对应的，OpenCode就是开启Plan模式。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBWib1Iw4zeiaepGlvFBlW61GTNtsMhSyTkHgnlk0fGrzac3C7qL8QxG1A/640?wx_fmt=png&from=appmsg#imgIndex=12)

然后，Agent就会开始调用skill-creator这个生成器，开始分析yt-dlp这个项目，然后开始规划要怎么打包封装成一个Skill。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBnXWVHu9HxqvYvB9hd5DKKqweRbhw7Poyjr0aCpBE6OWMbXYOz2AMhg/640?wx_fmt=png&from=appmsg#imgIndex=13)

规划了一通以后，OpenCode就分析完了，向我提出了几个问题。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBnWn23QQGWCWzyWl3b1tYJtAQQdxT2jfQL9LAJEt0AvqXQEQef0iawcw/640?wx_fmt=png&from=appmsg#imgIndex=14)

我也给出了我的回答。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBjdhIibNjMh7ib7bhDLnpiaO1JPcByMv5McD0XmByibYg1FDSFufgR4AZ3Q/640?wx_fmt=png&from=appmsg#imgIndex=15)

然后它就会继续规划，最终给我一个非常明确的计划。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBWibUs6ZqFf5SyCKzZibxhl4TqZ8oicv8iaOyuFcQ1RibqAjiba0ReAL8SGBA/640?wx_fmt=png&from=appmsg#imgIndex=16)

我觉得没有问题了，这个时候，我就会切换到正式的开发模式。

也就是这个模式，然后发一句话，开始开发！

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBKPpAswJuibs2lbsviarAs9Wnd1vWu3AZvc4WibBHVLVLWBZIia6ySTIoFQ/640?wx_fmt=png&from=appmsg#imgIndex=17)

OpenCode就会开始了。

过了一会，大概2分钟以后，这个基于yt-dlp的视频下载Skill，就开发完成了。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gB13puYmlaSukiaYItVffHCLl6pIEPVjpxGroTibWWRXXt3oEibDaJBLILw/640?wx_fmt=png&from=appmsg#imgIndex=18)

我们试一试。

比如OpenAI刚刚出的Youtube访谈视频，我想下载下来。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBTwictX7OoC3ibiaWG7DX3eE1TqPBqUGXwhPIAFJwcwq50qMmJXAFicR0bg/640?wx_fmt=png&from=appmsg#imgIndex=19)

直接就把链接扔给OpenCode就行，这里可以注意一个小技巧，就是所有的涉及到这种需要运行程序的Skills，在第一次运行的时候，都无脑推荐在OpenCode里使用GPT 5.2 Codex（如果你有的话），体验会比Claude 4.5 Opus好N倍。

大概就是：构建Skills的时候Claude 4.5 Opus，如果这些开源项目封装好了，在第一次运行的时候用GPT 5.2 Codex，后续就无所谓了。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gB7BS0iaXI6JshicB1FiaicQfHWLwbqhLfMVMC8sCyFOTjkJOhicrrrk0RmBA/640?wx_fmt=png&from=appmsg#imgIndex=20)

第一次运行，其实会遇到很多问题，比如说Youtube防爬机制很强，需要你装个浏览器扩展导出Cookie，比如要安装一些其他的项目等等，不过这些AI都会指导你干好。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBmPiaNCqPWSialglVEIGQYeibppFSVCicNdC3enibh8DAIJhjicR8ibjxKQ98w/640?wx_fmt=png&from=appmsg#imgIndex=21)

然后一顿操作，这个项目，就下载好了，全程大概也就几分钟。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBXTW0GgNQJaJKass0qjcLY9wOmz4hAl93132asR6lA6TxOyKSHbe2Zg/640?wx_fmt=png&from=appmsg#imgIndex=22)

之所以是几分钟，还是因为，这是第一次。

而后续，只需要，十几秒。

这时候，其实你还可以做一个事，就是，把前面的那些为了下载视频而做的一些事情和经验，直接跟AI说：

把这些经验，都更新到video-downloader这个skill里，下次就别这么慢了。

然后，它就会自己对他的Skill文件进行修改，下次，这些事情，就不用干了，随开随下，快到起飞。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBWmedQ5RicqPibeHV3aAhiaBn41QrE7NFYvMIKZl4kyATxEAEWicMbqOAvg/640?wx_fmt=png&from=appmsg#imgIndex=23)

这就是我的自己纯为了自己方便的一个skill全流程：

根据一个需求，用AI搜索github上得开源项目，把开源项目使用AI进行Skill化，首次运行后，寻找BUG和问题，重新迭代Skill，至此，Skill固化，形成我的主Agent中一个可靠的技能。

不止是一个下载视频的需求。

还可以是，把一个web项目，打包成一个轻量级的桌面APP。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBjwicWTiaFiaLZxulYRnDz4iaM0ThG3icNowBBicUoVp2sIX2jQhb66S37iaRA/640?wx_fmt=png&from=appmsg#imgIndex=24)

于是，找到了Pake。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBqAwnAib2PJBI6LpS1GIEAmH9Xx881bRqj6SXcNwUIKxgwGbLxkL9B9A/640?wx_fmt=png&from=appmsg#imgIndex=25)

Github上一个45k的超棒的项目，那就，直接Skill化，以后，你的网页开发完，直接就可以用Pake skill，一句话变成桌面APP。

你还可以，直接做一个究极万能的格式转化工厂。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBdeurdBS9oIibz5Hq0jMB4iaVz2G44d2BQ0stWF2ibe5PrM2nsOkSTEqzA/640?wx_fmt=png&from=appmsg#imgIndex=26)

直接把这些最牛逼的格式转化项目，直接封装在一起，做成一个万能的格式转化Skill。

从此，你无需各种奇怪的格式转化器，一个skill，解决所有。

你还可以，把ArchiveBox转成Skill，从此，你有想保存下来的网页，都可以发送给ArchiveBox Skill来以无数种你想要的格式，帮你保存下来。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBWouvhIJ6DvzoAkCyKPJ6bYuQgsQpujCRhsDq3hsnKZLxicdWviclegMg/640?wx_fmt=png&from=appmsg#imgIndex=27)

支持N种格式，真的。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gBCPFKVgrmLOgmJQLoScONPJ1wQFibjrxwnXnwDibqBcIkL3GwItTODWIQ/640?wx_fmt=png&from=appmsg#imgIndex=28)

甚至，你可以把著名的Ciphey，转成一个Skill。

从此，你就可以，在你的本地，配合Agent，直接破译密码。。。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURqgBBAMRyFuzOtGuo68h9gB6KpyIG8ken9hzxgVvOVzMYGIa3Lhue1fw30uJoeL3PK2XAv5DabAuA/640?wx_fmt=png&from=appmsg#imgIndex=29)

这些，全部都可以Skill化，全部都可以加入到你的Agent之中，成为，你最坚实的技能，成为，你最恐怖的弹药库。

而我提到的这些，仅仅只是Github上开源项目的冰山一角。

Github上牛逼的开源项目，那些人类的经验、人类的光芒。

本就灿烂如星海。

因为Skills的诞生，因为Agent的强大，现在，每个人、每个普通人，你的背后，都是全人类过去数十年的积累，只要你想，他就可以为你所用。

你无需三头六臂，你无需头上长角，你已经拥有了海量的知识和技能。

如果回到3年前的你的面前，你觉得，他跟你如今可以做到的事、如今的能力边界，还有任何可比性吗？

朋友，这样璀璨、这样伟大、这样能让你成为超人的时代。

真的不会让你兴奋吗？

******以上，既然看到这里了，如果觉得不错，随手点个赞、在看、转发三连吧，如果想第一时间收到推送，也可以给我个星标⭐～谢谢你看我的文章，我们，下次再见。******

\>/ 作者：卡兹克

\>/ 投稿或爆料，请联系邮箱：wzglyay@virxact.com

继续滑动看下一个

数字生命卡兹克

向上滑动看下一个