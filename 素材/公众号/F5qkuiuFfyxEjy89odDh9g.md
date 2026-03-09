---
url: https://mp.weixin.qq.com/s/F5qkuiuFfyxEjy89odDh9g
title: "GPT-5.4深夜发布，最适合OpenClaw的天选模型登场了。"
description: "OpenAI在读雄起"
author: "数字生命卡兹克"
coverImage: "https://mmbiz.qpic.cn/mmbiz_jpg/2jjfQoZLoqWic5Fc1kLLdoT0H1pWwgBaZGELTgOkN9SbK4ibFaInEvva8Fj54nh8WeWrBkMowjyspicZHDnzRZicoicbPhRWHnB9AoaMQM4zwNpE/0?wx_fmt=jpeg"
captured_at: "2026-03-08T06:06:44.786Z"
---

# GPT-5.4深夜发布，最适合OpenClaw的天选模型登场了。

原创 数字生命卡兹克 *2026年3月6日 06:36*

深夜凌晨2点，我刚准备睡觉。

然后，GPT-5.4，突然发布。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/2jjfQoZLoqVEzJyAleEmsibheicoUbNAO9Nm5L80ibILhPHiaw5KtrHMsAkaM9RsotPs9v8jdQPRVjJWpL3HhA8tLcs8l8rR6NS51ianNgD5VR4c/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1#imgIndex=0)

一下子激动的睡不着了。

真的，这真不是我天天咋咋呼呼啥的，我真的也很少会用激动的睡不着觉这种表述。

这是因为，我一直在等正式版的GPT-5.3或者GPT-5.4，来作为我的OpenClaw的首选模型。

理由特别简单，因为现代世界三十年，本质上基层都是代码，我们现在看到的关于计算机和互联网的一切，几乎都建立在代码的基础之上。

所以你可以理解为，代码能力，在很多时候，就代表着Agent能力的一根粗壮的腿。

一个优秀的Agent基座模型，在我的理解里，一般来说，需要三种都很强：

代码能力、世界知识、多模态理解。

当你这三个都能SOTA的时候，你几乎必然就是最牛逼的Agent模型，当然，还有一个重要的因素，就是价格。

在过去，Claude Opus 4.6，几乎就是Agent模型的代名词，因为代码、世界知识都很强，多模态能力虽然比不过Seed 2.0和Gemini 3.1 Pro，但是在一些场景里面，也够了，因为现在的Agent，跟现实物理交互还没有那么多，那个已经是具身智能的范畴了。

而我过去很喜欢的GPT-5.3-Codex，代码能力确实强，在做任务执行的时候，那简直就是指哪打哪。

但是最大的问题，这玩意是一个编程特化模型啊，世界知识就是一坨屎，连GPT-5.2都不如，所以OpenAI当时也是没办法，为了跟Claude打一打，只能加个Codex的后缀给放出来了。

所以你会发现，在规划能力上，是完全比不过Claude Opus 4.6的，但是最大的问题，其实还是因为世界知识的问题，就导致这玩意。

它说天书，讲的那些话，真的，我不是程序员出身，我看那个话，看的就真的超级费劲。

就比如说，我让他之前对我的一个AI热点网站的项目进行审查，主要就是review一下我的文档规范和我整个代码库。

然后，这哥们写的文档，我尼玛。。。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/2jjfQoZLoqXh2RbBL5A3v5eOnw60zIwbdmldTcvC3JnIgjyH9iaMy4z0sfBsynWg9f7UCRXTJKeBpVPKvqymybOCvCDhB6p4heT8EA8W99DI/640?wx_fmt=png&from=appmsg#imgIndex=1)

你再对比一下Claude Opus 4.6写的。

![图片](https://mmbiz.qpic.cn/mmbiz_png/2jjfQoZLoqVVPoiaf4nNyA1HFJCwZaZx2uWibG5ylgt7Kpg4MuCibq2JI99dYEv0G8hgyOh13wEG2NPEmUT7WfKM0AVfbeqFxOo2dm7NsAIAaI/640?wx_fmt=png&from=appmsg#imgIndex=2)

对比起来应该一目了然。。。

就是因为这玩意不说人话，世界知识也不行，所以，只是在Codex里面用用还好，但是你要是把它接到你的OpenClaw里面，去当做默认模型，你就知道啥叫灾难了，这哥们几乎没有人味，说起话来我想揍他。

所以我当时试了一下，就直接弃了，还是在我的OpenClaw里面，用的Claude Opus 4.6和Sonnet 4.6，做了一下场景调用。

那为啥说，我很期待GPT-5.4呢。

因为，Claude哪都好，但是，它贵啊！！！

它真的好贵啊！！！！！！

而且因为Anthropic这个呆逼，它把OpenClaw给疯了，所以我订阅的Claude的Max Plan的额度，是完全不能给OpenClaw用的，只能在Claude Code用，你想在OpenClaw上用，只能硬接API Key用。

但是大家都知道，Claude的API有多贵，那根本不是我们这种穷逼团队能用的起的，小规模用用还好，大规模用那公司直接破产了。

之前还有一条路是用反代，把Google家的Antigravity里面的Claude额度用插件代理出来，扔给OpenClaw用。

![图片](https://mmbiz.qpic.cn/mmbiz_png/2jjfQoZLoqWiczjWiavsFRLTFhib7QSBeWVd2XHzwFR88gnYNUVpnqrt2iccoPsw0eDEdoPIeI1LY7tRRTZN09YmEtzqLIuP5sP4h4GbPJ6P0SE/640?wx_fmt=png&from=appmsg#imgIndex=3)

但是后面Google开始大批量封号，导致也没办法用了。

我过年的时候Google账号还被封了，被迫用AI去给Google写了一份声泪俱下的邮件。

![图片](https://mmbiz.qpic.cn/mmbiz_png/2jjfQoZLoqUibhvyMCY8Ctyx4EiaBfBLqNOicAjsB2DuicFMeaOqlKbrmeuibM2qJefTX5QIeesdj8IFDyYol9USBA4ciaQeIa3rkM2iaoCeOfJxY0/640?wx_fmt=png&from=appmsg#imgIndex=4)

我说我错了，我再也不会了。

后面Google才给我解封，但是反代肯定是用不了了。

而OpenAI就不一样了，最开始Claude疯狂封OpenCode账号的时候，OpenAI大手一挥，就站了出来，说我们不封，大家全力使用。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpV8ww3u8wzg3LvvTG8brRP2VM4oISy7aulfsicRftInCzBRXnzsc6ecCn7zAwmvBhzeO5FJk69C8Q/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1#imgIndex=9)

这是御三家里，唯一一个这么支持态度的，可以用第三方的工具，调用Codex的额度的。

那对OpenClaw自然也不例外了，也是几个顶级模型里面，为数不多的，可以直接走登录的，其他的都得用API。

![图片](https://mmbiz.qpic.cn/mmbiz_jpg/2jjfQoZLoqVNRcRSEU2TkeelXaLhLROhdVp8Fusf6oTKElyahSYheRwq7wLibosHnhrga21FvjvMhvVE8YEGUg4b6ZTa2SKhDADXVgB4wuOU/640?wx_fmt=jpeg#imgIndex=6)

真的，OpenAI这会真的是大善人。

还疯狂的给Codex加额度。

![图片](https://mmbiz.qpic.cn/mmbiz_png/2jjfQoZLoqWaO1RfgS7tZX7QwWrOAeZlrNIMnQp5kCgVcoIhLq5v2sWyUosIqF7OHiaqjdcVzCCunyOC7R8A16gERcWNwiclEXoYcgDxJDw8s/640?wx_fmt=png&from=appmsg&tp=webp&wxfrom=5&wx_lazy=1#imgIndex=6)

所以啊，Claude在OpenClaw里用，好是好，但是不能用订阅额度，只能用API，贵的一笔。

OpenAI的模型倒是可以用订阅额度，但是GPT-5.2代码又不行，GPT-5.3-codex又不说人话。

你看，要多别扭有多别扭。

而这一次，GPT-5.4来了！！！

终于把这个短板给补上了！

代码能力跟GPT-5.3-Codex齐平，世界知识比GPT-5.2还要强，还能使用订阅额度，20刀就可以用的超级爽。

你就说，这不是最适合OpenClaw的天选模型，还有谁是？嗯？

从今天开始，用OpenClaw的，都把默认模型切换到GPT-5.4去，真的，信我。

回到GPT-5.4，老规矩，先看跑分。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/2jjfQoZLoqUZQU4WDXl3eSAcoZNbeI16lzEsCBVU54icTYI75ibjopjkc5XUNcCEMjZIXc0IcibDQdXSC5onJFsxCib0xO8hoibvwyWHyH20pKia4/640?wx_fmt=png&from=appmsg#imgIndex=8)

就很爽。

先看最关键的几个。

**GDPval：83.0%**

这个是测AI在真实工作任务中表现的，包括金融、法律等44种职业的知识工作。

GPT-5.4 Thinking拿了83.0%，Claude Opus 4.6是78.0%，GPT-5.3 Codex是70.9%。

在真实业务场景里，GPT-5.4不只是会写代码，它还能跟你聊业务、聊金融、聊法律、聊各种专业领域的东西。

而且是用人话聊，不是用天书聊。

**SWE-Bench Pro：57.7%**

这个是测AI解决真实软件工程问题的，不只是Python，而是测四种编程语言。

GPT-5.4 Thinking拿了57.7%，GPT-5.3 Codex是56.8%。

基本持平。

这就是我最想看到的结果。

代码能力保住了GPT-5.3 Codex的水平，世界知识又补上来了。

**OSWorld-Verified也是，75.0%。这个是测AI操作电脑的能力的，就是让AI像人一样，用鼠标点击、用键盘输入、在不同应用之间切换，完成各种任务。**

GPT-5.4 Thinking拿了75.0%，超过了Claude Opus 4.6的72.7%，也保持了跟GPT-5.3-Codex的持平。

而且，GPT-5.4操作电脑的速度，快的离谱。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/2jjfQoZLoqVSwDe0UAv0IsswTJcfs5DxuAVSHibuibBN8fA7wGtnJGaLnibFSWMwtSF9uETHnOibF3Nv3GFk5QvdEk8jHrdVVENzytdqAruVeh0/640?wx_fmt=png&from=appmsg#imgIndex=9)

看下这个没有加速过的视频，会更直观。

**ToolAthon：54.6%**

这个是测AI使用工具的能力的，也就是Agent能力的核心指标之一。

GPT-5.4 Thinking拿了54.6%，Claude Sonnet 4.6是44.8%。

差了将近10个点。

至于学术知识之类的，跟GPT-5.3-codex就没法比了，因为OpenAI自己也知道，所以，直接当时就没跑。

![图片](https://mmbiz.qpic.cn/mmbiz_png/2jjfQoZLoqWCaZPqtGfCOrSgXz6ibyfeHPfBwmwhCkiacmaIPV9UZTGQaEqticWwomYVuXwlxkDbuXSlbqbicib3QfHD1jFTWx8IXvB9zANRQN7E/640?wx_fmt=png&from=appmsg#imgIndex=10)

总之，翻译成大白话就是。

GPT-5.4 = GPT-5.3 Codex的代码能力 + 比GPT-5.2还强的世界知识 + 更强的工具使用能力 + 超级便宜的codex额度。

这四样加在一起，就是一个完美的OpenClaw天选基座模型。

然后还有几个很棒的特性更新：

1\. 100万token的上下文窗口。

这是GPT-5.4的一个大升级。

之前GPT-5.3的上下文窗口是40万token，GPT-5.4直接翻了一倍多，到了100万。

这对Agent来说太重要了。

因为Agent在执行任务的时候，需要保持对整个任务的上下文理解。如果上下文窗口不够大，Agent干着干着就会忘事儿，前面说的东西后面就不记得了。

100万token，基本上足够应对绝大部分的Agent任务了。

当然，OpenAI也不傻，他们说，超过27万token之后，你的额度就算两倍了。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/2jjfQoZLoqWEEXjSbgQgHsaUNqPZ76kQqGf6l4KKx7cV7mYDYAbTUj56G4WYsg8ZG6JcnHjIhtPkkhcmsryfhsz2RIcZUkibGSlxx4hM9ypY/640?wx_fmt=png&from=appmsg#imgIndex=11)

不过因为Codex给的额度实在是太多太多了，所以即使是2倍，其实也还好。

2\. 原生计算机使用能力。

这个是GPT-5.4的另一个大卖点。

OpenAI说，GPT-5.4是他们第一个内置原生计算机使用能力的主线模型。

它在编写通过Playwright等库操作计算机的代码方面表现非常的出色，同时也能根据屏幕截图发出鼠标和键盘命令。

也就是代码和视觉齐飞，我感觉，这个小龙虾接入以后，就真的可以，直接用视觉，操控你电脑上绝大多数的软件了，真的，原生操控，想想都激动。

他们基于此，还发布了一个新的skills，叫playwright-interactive。

允许Codex同时以代码和视觉的两种方式，调试Web和Electron应用。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/2jjfQoZLoqUYXlyCl1SzzF8CSd9gm9OX4p1jy760jQ2YK2cZv5VsKaQribSmHicVEOxL84qBA6gMHmUdCibcaMogrO3x6esnDaF5E6kZ1WoiasU/640?wx_fmt=png&from=appmsg#imgIndex=12)

网址在此，大家可以自行安装。

https://github.com/openai/skills/tree/main/skills/.curated/playwright-interactive

3\. 支持了工具搜索。

以前呢，当模型被赋予工具时，所有工具定义都会预先包含在提示中。

对于拥有大量工具的系统，这可能会为每个请求增加数千甚至数万个token，而且绝大多数的时候，都毫无意义，平白无故的导致成本上升、响应变慢，并在上下文中充斥模型可能永远不会使用的信息。

所以呢，这次他们也支持了工具搜索，就是GPT‑5.4不再直接接收完整工具定义，而是接收一份可用工具的轻量列表以及工具搜索功能。

当模型需要使用某个工具时，它可以查找该工具的定义并在当时将其追加到对话中。

就非常像Skills渐进式呈现的方式，目的很简单，还是优化上下文工程。

OpenAI在自己测试完以后，发现工具搜索配置在保持相同准确率的同时将总体token使用量减少47%，这个就非常牛逼了。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/2jjfQoZLoqWd3A2pQY2eHMyibNYJp8nib05W8EiadibiaFl1EqgKOAtE84gicAydHF4chYctNOncRZqWbX6bM1rdR7pUa8CnUI3mPzCrch6dwQ8lk/640?wx_fmt=png&from=appmsg#imgIndex=13)

GPT-5.4 Thinking大概就是这样。

这次他们其实还发了个GPT-5.4 Pro，我就不细说了，反正就是一切都更牛逼了，但是对于大多数人来说，太贵了，也没啥大用，必须得200刀的Pro会员才能用。

API的整体价格还是得说一下，虽然大家大概率用的都会是订阅的额度。

![图片](https://mmbiz.qpic.cn/mmbiz_png/2jjfQoZLoqUHrr0kO2Z5JawPcfichsIKAAJbF3OSCmLT1NI5dLy24xxYwf1O04FNHJBhcJIIWibHBCIicbxQCHgn3VibSw08pb6e0hrynMalU6k/640?wx_fmt=png&from=appmsg#imgIndex=14)

相比于GPT-5.2，价格是涨了的，但是还是比Claude Opus 4.6，便宜不少，Claude Opus 4.6的价格是$5/$25每百万token（输入/输出），GPT-5.4只有他们一半。

目前ChatGPT已经上线了。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/2jjfQoZLoqVeHKdU51VibL2PtzaftBdiaZ3mzzGb9jEDuEOzt0bkNDBuQExgeIzpsnh2W06LvCzZLBuibAXuDtzISicbGDtXvLleb9M8TvQ2Elw/640?wx_fmt=png&from=appmsg#imgIndex=15)

Codex也已经支持了，我自己在Codex里面粗浅体验了一下。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/2jjfQoZLoqWIfgkd65BjPaMxlzLaQKic9icLIKNAfF7XtI4yemLXv1DiayQzYr2zDoSLZTmCxaA6u1Bh5Nad0g5UeZXfNY8rBLQV8JS1tm53iac/640?wx_fmt=png&from=appmsg#imgIndex=16)

首先扑面而来的，那自然是清新沁人的人话。。。

比如我让它去把OpenAI官网的视频给扒拉下来，你看看这个发言：“这种活最烦”，“省的跟Cloudflare互相折寿”。。。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/2jjfQoZLoqWfvfibpOTOCZm41EDH9qq9U4qgibDOV0cLibXxZZyjicm3bS0jZICnIV7uuYqDFFR0tPwUYNJH4hu1fVqRQyA0GkmaE9NUP828v4U/640?wx_fmt=png&from=appmsg#imgIndex=17)

还有这个。

真的，Codex的输出，我真的能看得懂了。。。

![图片](https://mmbiz.qpic.cn/mmbiz_png/2jjfQoZLoqWvRoC9piaPRCSj2GWWL6dDCCuZT1IGy6DYa2pIJBdAbRuoILDlZDbaX77WXBKwd234TYJt4A3leMfhkbuNykKWKwiaZwVoica5uE/640?wx_fmt=png&from=appmsg#imgIndex=18)

做出来的东西，前端审美有了不错的进步，但还是不如Opus 4.6和Gemini。

![图片](https://mmbiz.qpic.cn/sz_mmbiz_png/2jjfQoZLoqVFvjWoQwgQtkbKa6tiaeNRFm93PvepRWXNq4oj7551M9wEib2R3P5icibpqwufKUfdaVc2kzrIicTB1biagkibp3iblZvjboDuKq0zqXs/640?wx_fmt=png&from=appmsg#imgIndex=19)

写作粗略测了一下，还是一股子莫名其妙的爱用排比句的诡异的味道。

奇奇怪怪。

然后有点可惜的就是，我等到了凌晨6点多，OpenClaw目前使用Codex登录的方式，还是没有支持GPT-5.4。

![图片](https://mmbiz.qpic.cn/mmbiz_png/2jjfQoZLoqX9vl5YLJnzxIxltrUf9xla0B9JAHoWWDSHCeXoUY3JpHrVshkiapmxdxibnhvnxUrdgmLD0EwZ4T3ownlibwhXwTyr3Wmzjb0Ql8/640?wx_fmt=png&from=appmsg#imgIndex=20)

这就导致，我还是没有机会测GPT-5.4在小龙虾上的效果。

不过估计我一觉睡醒，估计小龙虾就支持了。

因为社区里已经看到很多用户在催了，而且先行官们，都普遍反馈效果很好。

坐等支持，我真的已经迫不及待了。

又是开心的一晚。

如果你也在用OpenClaw，那记得OpenClaw支持了以后，把默认模型切换到GPT-5.4。

如果你还没用过OpenClaw，那正好，现在是一个很好的开始时机。

毕竟，有了GPT-5.4这个天选模型，体验只会更好。

2026年，真是疯狂的一年啊。

睡了。

******以上，既然看到这里了，如果觉得不错，随手点个赞、在看、转发三连吧，如果想第一时间收到推送，也可以给我个星标⭐～谢谢你看我的文章，我们，下次再见。******

\>/ 作者：卡兹克

\>/ 投稿或爆料，请联系邮箱：wzglyay@virxact.com

继续滑动看下一个

数字生命卡兹克

向上滑动看下一个