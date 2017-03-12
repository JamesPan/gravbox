---
title: 终于学会承认自己做不到
date: '2017-01-21 23:37'
taxonomy:
    category:
        - blog
        - Study
    tag:
        - Thinking
header_image_file: 'https://ws4.sinaimg.cn/large/006tNc79jw1fbyp1ejnfyj30go06sgmb.jpg'
comments: true
---

要说 2016 年我在技术上的最大的收获，当属心态发生了转变。在此之前，我在技术上没有一个明确钻研方向，为了解决问题嘛，碰到什么问题就搞定什么问题，一时半会搞不定就绕过去，也能获得很好的结果。到头来却是，我成了一个「全栈」工程师，不知道我真实水平的人以为我能力很好，什么烫手山芋交给我都能得到超出预期的好结果。我自己却感觉到彷徨和困惑：几年之后，人们提起我的时候，想到的是一个干活很靠谱的全栈，还是一个别的什么？

===

我想要成为一个真正的技术专家，而不是一个顶着技术专家头衔的「全干工程师」。带着这样的理想，我加入了阿里云的云数据库团队，然而并没有什么平台是能承诺一定让你成为专家的，平台能够提供的是高难度的问题，高水平的同僚，剩下的一切都需要自己去证明，机会也要自己去争取。

仅仅懂得比别人多，是成不了专家的，最多就是成为咨询师。大老板跟我说，专家就是要能搞定别人搞不定的问题。为了能够搞定别人搞不定的问题，你要成为这个领域里的第一，开始是团队里的第一，后来是公司里的第一，最后是行业里的第一。

属于我的领域在哪里，我不知道。没关系，先从把工作做好开始。

后来因为对工作中一些效率上的工具不满意，自己在周末造了两个轮子，不曾想无意中解决了团队里说了很久却一直没能解决的问题，然后就这样获得了团队里的第一届「创新之星」，奖品是一台大疆无人机。

![](https://ws4.sinaimg.cn/mw1024/006tNc79jw1fbyokls6nhj30lc0sgn3y.jpg)

> 有些事情别人半年都搞不定，你两天就做出来了；有些事情你半年都搞不定，别人两天就做来了，我希望每个人都能做自己最擅长最喜欢的事情，把事情做精做深，真正发挥每个人的价值

什么是我最擅长的事情？我不知道。我不是 MySQL 专家，不是 Redis 专家，不熟悉 NGINX，不熟悉 Kafka，不熟悉任何一个基础设施或者中间件，不是任何一个数据库或者操作系统的老司机，甚至我做为 Java 工程师也不熟悉 JVM，更不知道 Servlet 是何方神圣，做为 Python 工程师也不熟悉 Python 解释器。但是我在需要的时候能魔改 Druid 连接池底层的 SQL 解析，能魔改 pip 打造出一个能从 Nexus 仓库上传、下载、安装 Python 模块的 mpip。

于是到头来我还是一个什么都拿不出手却什么都干的渣渣？回想着大老板跟我说的话，我似乎发现了问题的结症：我对自己的要求太多，以至于什么都想做最终什么都做不好。

于是我开始学着承认自己能力不足，学着承认自己搞不定。在过去，承认自己解决不了问题总是让我感到羞愧，如今却可以心安理得地承认自己搞不定，让同事找老司机看问题，然后自己跟着在一旁学习，而不是自己抱着代码默默排查个老半天。

心态转变之后，突然整个世界都变好了。

我虽然还不知道自己擅长什么，但是我至少知道了自己不擅长什么。走出舒适区就是要去做自己不擅长的事情，可是我连舒适区都没有，连擅长的领域都没有，还是先找到舒适区吧。

今年有大半年时间我没怎么写生产代码，而是在做一场旷日持久的线上变更，每周有两三天通宵达旦地工作，以至于我在做变更的那段时间里，都不怎么会写代码了。但是那段时间里，经常有同事找我讨论 Java 系统架构、HTTP API 的设计，这让我意识到，原来我在 Java 系统设计、微服务架构方面的经验，甚至于之前在菜鸟网络时见识的各种淘系中间件、各种内部轮子的设计，可以给同事们设计系统的时候做为参考，可以分享我之前掉过的坑、做过哪些事情避免掉进坑。

我突然发现，只需要动动嘴皮子给个方案，然后由别人坑哧吭哧去把系统实现出来，这种感觉真的很奇妙，但是有毒！这不就是我们说的 PPT 架构师吗！据说菊花厂的架构师就是这样，只出设计，不写代码。那段时间也曾经和同事开玩笑，说我已经写不动代码，干脆转型做 PPT 架构师，专门参与技术方案讨论就好了😂

后来，旷日持久的变更终于做完了，零故障，很棒，超出预期。因为做这个变更，在一些项目上欠下了债，之前是厚着脸皮一拖再拖，现在从变更里出来了，债得还。还债之路也并不平坦，老板让我开始介入一个重要的底层系统的工作。原本以为能够等到我把债还完才开始介入，没想到债才刚开始还，我就在一次讨论中贡献了一套技术方案，然后在这个系统里坑哧吭哧写了一个月才把这个方案给实现了，前几天刚刚交付测试。我从零开始给这个系统设计了一个全新的分布式架构，号称能解决之前老架构上解决不了的各种问题，还和同事一起在这套新架构上支持了一个全新的业务，老业务的迁移也在开始规划。

终于等到了一个机会，做出一个能够代表自己真实的工程能力的系统。原来，在这之前所做的一切工作，获得的一切认同，成为一个靠谱的全栈工程师也好，和同事通力协作零故障地完成超级大变更也好，都只是在为这个机会做准备，之前做的一切日常而琐碎的系统维护，也显得不是那么琐碎无聊。

当你不知道该做什么的时候，可以先把手上的事情做好。简单的事情做不好，就不会有机会去做不那么简单的事情。

事了拂衣去，深藏身与名。交付了一个牛逼闪闪的新架构，交付了一个新业务，本以为可以悄悄的退出来，继续还我的项目的债。但是天不从人愿，CAP 定理让人们中毒太深，提到分布式系统言必谈 Paxos 和 Raft，以至于我搞了一个和 Raft 毫无关系的系统，也被同事询问系统设计的理论基础。

对我来说设计一个分布式架构的应用，和设计一套微服务架构的应用，都是纯粹的软件工程，除了一个是系统内部通信完成状态转移，一个是系统之间通信完成业务请求之外，没什么本质区别。Storm 和 Kafka 之类的分布式系统，不也没有理论基础么。但是换个方向一想，我做的系统居然已经重要到需要理论来保证其正确性的地步了，如果我真能给出理论或者什么证明，是不是也就可以自称「略懂分布式」了？

一直没认真看分布式方面的书，终于吃了文化的亏，就趁着这个机会好好补课吧，或许分布式系统设计，可以成为我所擅长的领域。