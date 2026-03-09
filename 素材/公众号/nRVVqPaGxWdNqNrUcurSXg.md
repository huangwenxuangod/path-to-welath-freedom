---
url: https://mp.weixin.qq.com/s/nRVVqPaGxWdNqNrUcurSXg
title: "一文带你看懂，火爆全网的Skills到底是个啥。"
description: "自由的味道"
author: "数字生命卡兹克"
coverImage: "https://mmbiz.qpic.cn/mmbiz_jpg/OjgKEXmLURpC92KictnrYXV7jWfAoB5uj3dkHb0zFQmjtCUibVGQwQq3cPAmrxSSGnsBdqk7hagBia8picfJBWF9wQ/0?wx_fmt=jpeg"
captured_at: "2026-03-08T06:25:59.812Z"
---

# 一文带你看懂，火爆全网的Skills到底是个啥。

相信大家最近，都都在各种地方看到一个单词。

这个单词叫做，Skills。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujdsEkwNib4Cg933eO4Mticxn97Sbib4xHUhjJQH4Eb52piccVOj4hj3us0w/640?wx_fmt=png&from=appmsg#imgIndex=0)

各种github上被疯狂star的仓库，很多也都是skills相关。

比如这个这个包含50多个Claude技能的仓库，已经18K了。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujFKLnuVWVckoSg2DZzA8ZUNomwqKyqVHibedmiaRfL62c9qWlZU2f3hHw/640?wx_fmt=png&from=appmsg#imgIndex=1)

还有这个叫superpowers的项目。

一个基于各种skills包装之上的开发工作流程，也18k了。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujczWLpc0aFM5QDugQhXrZyoHFmQa2ajxpkAlEjqM7MpHALA57jlxmWQ/640?wx_fmt=png&from=appmsg#imgIndex=2)

skills的热度，现在在AI圈里，都有点不亚于当年的Prompts。

23年24年，大家都在分享各种各样的Prompt模板。

而现在，大家都在互相分享各种各样的skills。

很多人这两天也都在后台问，skills到底是个啥，跟Prompt、MCP、到底有啥区别。

所以，也花了一些2天时间，来写这篇文章和教程，希望能通俗易懂的带你看懂，啥是skills，以及，这玩意到底怎么用上。

话不多说，我们开始。

Skills，翻译过来就是技能，字面意思上非常简单，给Agent用的技能。

注意我的定语，给Agent用的技能。

先给大家看两个，我们公司内部用Skills做的两个我感觉还算有趣的案例。

直观的让大家感受一下，Skills他能干啥。

第一个案例，是我们的AI选题系统。

很多朋友都好奇，我是怎么自动化找选题的，方法论我们当然是有非常严格的方法论，但是自动化的工具，肯定也是需要的，毕竟选题这玩意，其实就是海量输入到少量输出的转化漏斗，你先要足够多的信息，才能找到还可以的选题。

按过往，我们一个人来找的话，每天至少要浏览两遍推特、Reddit、Github、buzzing、The Information、微博、知乎、小红书、B站等多个网站平台，筛选出有价值的热点，再思考这个事件是不是值得写，切入角度又是什么、标题又是什么。。。

说实话，这个过程过去经常要花费2-3个小时，会大量浪费我日常自己做项目和体验产品的时间。

于是，之前12月呢，我们就用Skills，手搓了一个AI选题系统。

里面包含1个 Agent（总控中枢）+ 3个Skill，现在，每天我只需要说一句：开始今日选题生成。

这玩意就会全自动的：

第1步，一个热点采集skill采集全网热点，从多个平台抓取最新热点。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujCTjCYbTJO0TB2822TSGBSPrwPquvfOluPQ8J9oiaptuh2MXzoJGRhsw/640?wx_fmt=png&from=appmsg#imgIndex=3)

第2步，用一个选题生成的skill自己分辨，然后筛选并生成TOP10值得关注的选题，包含"事件描述+核心角度+标题"。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujLcBNDFyvN36Vw68SfllNnFq68DYaCRDdnPIm3qFlReaQKRqHMZj4lg/640?wx_fmt=png&from=appmsg#imgIndex=4)

第3步，自己开始使用我们的方法论，开始审核上一步输出的所有选题。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujaIWyWoHwduantaWWbWQsebUhT1PImnHYKgL6krzNXru9icTUjs1foibg/640?wx_fmt=png&from=appmsg#imgIndex=5)

最后一步，当选题审核不通过时，系统不会结束，而是由审核Skill给出不通过 + 修改意见，接着主 Agent 读取反馈把修改意见作为上下文，重新调用选题生成Skill修改不通过的选题，再次进入审核流程，不断的迭代，直到审核通过为止。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujoYiaEfIJZoMcqykKwfRkDdjAEzqiaIrX1IMCxVic3yzuNq3KtlhKYnulQ/640?wx_fmt=png&from=appmsg#imgIndex=6)

流程特别简单。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujRibok4ibEEJSB4PhH6hoHe4jVQC1eh9hgxN9icXVL3tnvXJzShzUhZGDw/640?wx_fmt=png&from=appmsg#imgIndex=7)

这个看着是不是有点像Workflow？

其实没错，Agent+skills，在很多时候，就是workflow的一种呈现，甚至宝玉老师在一篇文章中的原话更为激进：“几乎所有能用 workflow 完成的AI任务，都可以用Agent + Skills实现。”

另一个任务，我做了一个整合包生成器。

就是我自己因为确实编程小白，很多github上的开源项目都没有前端界面，又需要各种各样的环境，实在是搞不明白也用不了，我就想要一个整合包能开箱即用。

所以我自己一直想有一种方式，能给一个Github链接，它就能帮我把整个项目，打包成一个本地整合包，用脚本一键启动，前端是一个好看的魔改过的界面。

所以，我就搓了一个skill，我称为，整合包生成器。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujThYN7GxMibpyQv1VH5DvWNnyLRyGFCED9vbfKvcDsiap8wDgXic84rzeg/640?wx_fmt=png&from=appmsg#imgIndex=8)

大概的的Skill结构。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujXpY0sVdYyDHPcyp9VkMKD9ZCMk1Stz0uyTeEdZ2icozia95DPenU7EHQ/640?wx_fmt=png&from=appmsg#imgIndex=9)

比如这个著名的Manim项目，是一个用于精确程序化动画的引擎，专为创建解释性数学视频而设计。

我就直接一句话扔到OpenCode里，说要帮我做成整合包。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujm8siaeGKQZRqnL52ibib7uzPa8xQicTOXbRSVlAspAY3PGDHzEAibLb8GOg/640?wx_fmt=png&from=appmsg#imgIndex=10)

在规划完，用各种agent和这个skill，列了20个ToDoList。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujbkWJyjfep7KksK3S3TFD0jicB3jBgsSa98f43bdt5mGaE6ZXRibKE8og/640?wx_fmt=png&from=appmsg#imgIndex=11)

又开发了十几分钟之后。

一个本地的整合包就完成了，解压，运行脚本，打开前端项目。

然后...就报了个错。

不过无所谓，把错误日志，复制回去，直接让AI解决一下。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujywu6ibVHXapoFBBjnVACPyL1r4F8euuJecRZ4xEWjbSeQk66AJKcmCw/640?wx_fmt=png&from=appmsg#imgIndex=12)

再打开，搞定。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujXZAgQwRDw8l39eyWhNqvqcdq57qjEWDnur3HB54O4hAHKL36krraicA/640?wx_fmt=png&from=appmsg#imgIndex=13)

现在，我可以直接把大多数的Github上的没有前端项目，直接生个前端，给我这种小白用...

完美的解决了我这种编程小白又菜又想用各种大佬的开源项目的痛点。

看完我们的case之后，相信你也大概能明白，Skill能做什么有趣的东西了。

说实话，到现在我也依然觉得，Skills这玩意的价值，还是被大大低估了。

无论你是专业者，自己把自己的经验和workflow封装成各种各样的skill，还是跟我一样的普通小白，把一个一个的需求封装成skill方便未来持续调用。

这玩意，都有莫大的潜力。

首先，非常简单的跟大家收一下，Skills到底是个啥。

Skills这玩意，是去年也就是2025年10月，Anthropic在Claude Code上支持的特性。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujenibTJT8Dm8qHkYJicnJosGl84xZl2mnhYWYBjf90UiawmTeC2wUzbljw/640?wx_fmt=png&from=appmsg#imgIndex=14)

后面之所以爆了，是因为12月18号，他们把Skills当做一个标准，直接开放了，所以，大家纷纷接入。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujiaadpiaKaiaAV89nMB4KhMYPUf8H7RPx3rPd8mekLvrOSDTRTXnibXIlKg/640?wx_fmt=png&from=appmsg#imgIndex=15)

目前除了Claude Code自己之外，我昨天推荐的OpenCode也完美兼容Skill，Codex、Cursor、Codebuddy等一些编程工具，也基本上都兼容了。

技能不同于传统的Prompt只有一个markdown的文本，在里面，其实包含了各种各样的东西，比如有Promtp、参考文档、脚本之类的在Agent需要时可以加载的资源的文件夹。

所以，在形式上来说，Skills是一个文件夹，不只是一个文本，这个需要清楚。

就比如我的那个整合包生成器，里面就有蛮多脚本。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujiaF5rCGzpIttcEGic2M29sX8OwWhGy8KonsKCOsxkyibw9xswzMO73xXQ/640?wx_fmt=png&from=appmsg#imgIndex=16)

你可能会说，还是很绕，很难理解。

那我再用故事举个例子。

就比如说，在工作中，让你带新人。

你可以把Agent想成一个刚入职的实习生，很聪明，理解能力很强，嘴也很甜，啥都能聊。

但你真让他干活，他最大的问题从来不是智商，是不熟你家规矩。

而Prompt是啥呢，Prompt就像你站在他旁边，当场口头交代任务。

今天让他写一段公众号开头，明天让他把语气改得更克制一点，后天让他按你要的结构写一页 PPT。

它天然适合一次性的、临场的、随时变的指令。

同时，它也天然有个缺点，就是你一关对话，它就像你刚刚说过的话一样，木得了，Prompts是对话里你当下给的自然语言指令，临时、反应式、只在这轮对话里生效。

而Skills，就像你给他一本公司内部的那种SOP手册，你们肯定见过无数了。

而且这手册不是那种一张长到让人窒息的Word，它更像一个知识库般的文件夹，里面可以放规范、脚本、模板、参考资料等等，Agent呢，会在需要时自己去翻。

这里有个特别关键的设计，叫progressive disclosure，中文名叫渐进式披露，在过去移动互联网时代，可以说是我们做用户体验设计时的最高法则之一，你们每天用的菜单栏，就是渐进式披露的最常见的设计。

比如点头像，进入到菜单栏，再从菜单栏，点设置，最终进入到复杂的设置界面。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujCSkCsDKAENkD1RkIHqoGePIujJ7uMk0MI69wUoprhWFKDmOOWwIz8A/640?wx_fmt=png&from=appmsg#imgIndex=17)

目的特别简单，不是在一上来的时候，给用户提供大量的信息和选择让他认知负荷爆炸，而是将这个过程分解成几部分，让用户集中注意力在当前的事件上，从易到难地引导用户。

这样不仅可以确保用户不会被新信息淹没，还可以逐步分解、引导用户在认知负荷最低的情况下，处理任务。

本质上，其实就是人的瞬时记忆区太小了，一瞬间只能接受最多7±2个信息块，而AI因为受限于Token，其实在本质上，是一模一样的。

所以渐进式披露放到Skills上，就变成了，先放目录，再放章节，最后放附录。

Skill的元信息先加载一小段，让模型知道“有这么个手册，适用范围是啥”。

当它判断这次任务真用得上，再把完整的SKILL.md读进上下文，要是还不够，再按需去读你在文件夹里附带的其他文件。

用这样的方式，不仅可以保证Agent能准确的执行任务，还可以在长轮对话中，省下大量的Token，因为在大模型的交互中，对话越长，模型越笨，这几乎是个共识，Token这玩意，在Agent架构设计上，真的就是寸土寸金。

所以，你就能看出来，为啥我一直强调说，Skills是给Agent用的技能。

它其实做的一直就一件事，把你的流程性知识变成可复用的能力包，然后在Agent需要的时候，随叫随到，稳定发挥。

而MCP这玩意，跟Prompt和Skills完全就不一样了，它不负责教新人怎么干活，它只负责，给新人开门禁卡。

比如你现在遇到的很多痛点，本质是这个新人牛逼到爆炸但是就是进不去你们公司的仓库，因为他没有权限，没有仓库的那个门禁卡。

MCP就是那个门禁卡，能让AI应用安全地连接外部系统，调用外部的一些能力。

听完了上面的故事，我相信你现在肯定清楚，Skills、Prompt、MCP的区别了。

那明白是啥了，大家也都知道，Skills本质是个文件夹了。

我们就可以来看看，一个基本的Skill的基本配置是个什么的样的了。

一般来说，一个完整的Skill，包含以下文件：

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujc7JYzibl7AuSbQ5SO78Qw1tibY0oZssbplG0etktGrnJy6RxxokPlNdQ/640?wx_fmt=png&from=appmsg#imgIndex=18)

**重要提醒：**

1、文件夹名称必须是 **小写字母+连字符** ，例如 hotspot-collector（不能有空格、大写）。

2、SKILL.md是 **唯一必需的** ，其他都是可选的。

SKILL.md 是核心文件，它的结构是固定的分为两部分 **：**

**1、** **YAML** **头部** （必需）：用---包裹，包含 name和description字段，这是 OpenCode用来识别 Skill 的名片。

**2、** **Markdown** **主体** （必需）：详细的工作流程，输出格式要求，示例等。

```markdown
---name: 你的skill名称description: 简要描述该技能的功能以及何时该使用它---# 你的技能名称## 指令 (Instructions)为 OpenCode提供清晰、逐步的操作指南。## 示例 (Examples)展示使用该技能的具体代码或操作案例。
```

最最核心的，其实就是description这个字段了，就是描述Agent会在何时如何调用你这个skills。

这块一定要注意，别把一些Prompt的坏习惯带过来，一定要始终使用第三人称。

因为描述会被注入到系统提示中，不一致的视角会导致发现问题。

优秀的："处理Excel文件并生成报告"

不太行的："我可以帮助你处理Excel文件"

不太行的："你可以使用这个来处理Excel文件"

且，尽量包含你的触发关键词，同时整个将SKILL.md的正文，一定要保持在500行以内，这样效果菜最好。

比如我那个整合包生成器的SKILL.md文件。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5uj5iadXKqJKabrvrqhoia6ZCTL8M13hLaJSjLZ6z7r7ZwxDCNr9tAggFzw/640?wx_fmt=png&from=appmsg#imgIndex=19)

是不是有点晕了，此时可能很多朋友就会说，停停停，别跟我讲这些了，我知道要写这些，但是太麻烦了，这么多东西都要我自己设，好麻烦，又没有那种能帮我直接生成一个Skill的Skill。

你别说，还有真有。

Anthropic官方自己就开源了一个Skills仓库，里面有不少极度实用的Skills。

网址在此：https://github.com/anthropics/skills

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujic9aYo16kanW4TqPyY6HNwXLqlY8X8yAygHlmSHqWgzZiaGthvo8bHIA/640?wx_fmt=png&from=appmsg#imgIndex=20)

这个Skills文件夹里，就是Claude官方，自己做的Skills。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujz8XKbAWiabohtmkNwUW9n5seMR9ThTXncPfsv9FDZU0TYZenKkW2Zeg/640?wx_fmt=png&from=appmsg#imgIndex=21)

我也简单整理了一下大概的作用。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujQuWbeX04nnPKRl2FbHLtjFfe2RiazQOVnQEeWy71Laheu66x8ILZgeQ/640?wx_fmt=png&from=appmsg#imgIndex=22)

比较推荐安装的就是docx、frontend-design、pdf、skill-creator、xlsx这些几乎所有人都用的到。

里面能生成Skills的Skill，就是这个skill-creator。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujEh5p3NjnQ57wJCbyeESFt4KeYlX7IQb7wVavRZTFntQptllViagXpeA/640?wx_fmt=png&from=appmsg#imgIndex=23)

安装这个Skill也特别简单。

有两种方法。

1\. 直接使用命令。

我们打开Claude Code或者OpenCode，我这里还是用OpenCode举例子。

直接把这段Prompt，发给AI。

```ruby
安装这个skill，skill项目地址为: https://github.com/anthropics/skills/tree/main/skills/skill-creator
```

然后，就装完了。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujiaLQia51sjcpD81ZCfxPodPr5icibw8zph3D74mZQsZCiaqibS18eetjFPIA/640?wx_fmt=png&from=appmsg#imgIndex=24)

你想要安装Claude官方的其他的Skill，就把链接换了就行。

2.第二种做法，就是把Skills文件夹，直接拖到你的本地目录里。

地址如下：

Claude Code：~/.claude/skills

OpenCode：~/.config/opencode/skill

比如我的Mac电脑的路径：/Users/khazix/.config/opencode/skill

Windows的话，就是这。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujZBavqFysKgMskCsibL69A83Q4xFYsGSo03KQIibevlSC8bESqB0lj8YQ/640?wx_fmt=png&from=appmsg#imgIndex=25)

这里注意一下，初始是没有skill文件夹的，要自己手动创建一个，所有项目都能共享放在全局目录的Skill里，建议大家可以把所有的skill都选择全局目录生效，这样在任何文件目录下打开Claude Code或者OpenCode都可以识别到你所安装的skill，也更加方便，如果是开发者自己有特定的分区，那另说。

装完以后，OpenCode记得退出重进一下，Claude Code不用，2.1.0版本更新后就有Skills热重载了，非常的香。

当你配置好skill之后，你就可以直接运行了，运行Skills特别简单，直接通过对话OpenCode就会根据你的需求来调用对应的skill来完成你的任务。

就比如我那个整合包生成器的Skills，你直接说你的Promtp，先用Plan模式规划一下，确定了所有的文档之后，直接切换模式，然后开干就行。

![图片](https://mmbiz.qpic.cn/mmbiz_png/OjgKEXmLURpC92KictnrYXV7jWfAoB5ujzmjHFdr1ib2TuYgsAXKfNJV2eVLNhCv6P1sKx6aXZ5p4F715ibGqfeNw/640?wx_fmt=png&from=appmsg#imgIndex=26)

写到这儿，你应该能感觉到，Skills这波热度，真不是圈内人又在发明新词。

带新人最爽的状态，从来都不是他能说会道。

而是我给他一套手册，他自己能翻，能执行，能自检，能迭代。

你少说一句废话，他多交一份结果。

Skills也一样。

今天你就可以，把skill-creator装上，然后把你最常用的一个动作固化下来，比如选题筛热点，比如把报错日志变成修复方案，比如把一堆链接变成摘要和观点。

做完这一个，当它运行起来的那一瞬间，你就会懂，Skills的价值，在于复用。

明天你会开始想做第二个。

后天你会想把所有的流程全都搬进去。

到那一步，你就进入了另一个状态。

自由，创造的状态。

******以上，既然看到这里了，如果觉得不错，随手点个赞、在看、转发三连吧，如果想第一时间收到推送，也可以给我个星标⭐～谢谢你看我的文章，我们，下次再见。******

\>/ 作者：卡兹克

\>/ 投稿或爆料，请联系邮箱：wzglyay@virxact.com

继续滑动看下一个

数字生命卡兹克

向上滑动看下一个