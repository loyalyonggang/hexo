title: 我眼里的架构师
date: 2015-12-17 18:03:01
categories: 日薪越亿
tags: 架构师
---

![architect](http://sphenginx.github.io/images/architect.png)

攻城狮，美其名曰架构师。相信每家公司对架构师的定义和要求都不一样，今天我仅以我的角度，聊一聊我眼里的架构狮。

几年前，我对架构师的印象，停留在：画漂亮的设计图，研究高性能，技术攻关一把手。反正就是各种技术高手的标签都可以贴上去。最近两三年，和自己做的事情、职责多少有一点点关系，思路发生了一些变化，总结下来，我觉得架构师的关注点应该是：  
+ 架构团队
+ 架构技术
+ 架构流程规范
+ 架构产品
+ 架构客户

## 架构团队

没有团队，就没有架构师。

### 架构师需要关注并不断优化团队的结构。

一个20几个人的开发团队，架构师作为团队的主角，需要能最大化团队的效率：包括把什么样的人放到什么样的位置和哪些人做哪方面的对接；根据团队成员的特点如何做技术配比和责任分工，如何组织好团队协助自己完成技术攻关、技术研究和选型。

### 架构师还需要时刻关注团队的成长路线。

对每个开发组的lead，帮助他们在最短的时间内达到他们的下一个技术制高点，同时帮助他们筛选出组里的后备军，在合适的时间，给后备军独立攻关亦或带小团队成长的机会。

## 架构技术

做为架构师的看家本领，架构师需要做到的当然是技术过硬、视野够广。至少在某一个领域有一技之长，同时不失对当前流行技术的了解、深入把控。主要体现在：

### 技术选型

选择合适的技术，本身就是仁者见仁、智者见智。但是，对架构师的挑战，在于你是否是在任何项目、任何产品上都坚持只用自己熟悉的技术。接触过很多“架构师”，坚持的认为熟悉的就是最棒的、不管黑猫白猫抓到耗子就是好猫。这是我坚决反对的观点。既然是架构师，技术上必然有一技之长，要么编程牛逼可以从应用层写到内核层，要么对数据有很强的分析能力，要么对分布式高性能有很多的研究和经验，要么是客户端架构师对iOS/Android 有深入的研究，但是，不管是哪一个领域的高手，都不应该也不能够丢失对新技术的嗅觉敏感度。好的架构师，一定是在“老的技术”的保障下，逐步的研究、采用、推广当前流行的新技术，然后在合适的时间，完成新老技术方案的升级。同时，还需要考虑产品的特点、团队的结构以及自己对选用技术的把控能力。

### 平台选型

我把平台选型拎出来，是因为最近两三年云的快速的发展和变革。做为“有追求的架构师”，你是坚持创造一切，还是拥抱云服务？我是一个云服务的坚决拥护者，道理很简单，让合适的团队做合适的事情，同时，对于中小规模的互联网产品线，利用远比创造成本更低。所以，我们自己的产品，能托管于云端的，坚决不自己构建。目前我们在用的云服务：阿里云托管所有的主机，阿里云RDS托管数据，阿里云OSS数据备份，阿里云ODPS大数据计算，七牛云文件存储和文件CDN，云片发SMS短信，Send Cloud发送邮件通知。

### 持续交付

再牛的架构师，如果不能带领团队把产品交付出来，即使拥有再牛逼的技术、技术选型和平台选型再高大上，也于事无补。架构师需要平衡好架构设计、产品的交付周期、技术方案的难易程度。

### 架构师失业论

今天和团队聊天的时候，提到了“架构师失业论”。我一直认为，当今技术和平台的变革，不出几年，架构师们都可以统统失业了。公司付给架构狮们高额的薪水，可以完全足够用来支付给云平台。未来，云将主导一切，托管一切。你看看AWS的Lambda，你看看现在活起来的Mesos，已经可以让开发者忘记内存、CPU、磁盘的存在了，随着访问量自动无限扩容。你说，还要你架构师有何用呢？

## 架构规范

规范在很大程度上绝对了开发团队的开发效率、开发团队和产品团队的沟通效率。在我看来，规范包括但不限于：

### 开发规范

包括代码的目录结构规范，编码规范，SCM管理规范，包管理和工具规范等等。

### 发布规范

又包括代码版本管理规范，开发环境、测试环境、Staging环境以及生产环境要求，上线发布的流程等等。

### 沟通规范

包括团队沟通的工具、形式，代码review的方式方法等。

我们目前在使用Git，同时，遵循 git flow，代码review走merge request，CI集成gitlab CI & docker runner/Jenkins。合理利用工具，可以是开发效率事半功倍。

## 架构产品

产品和架构师有什么关系？架构师除了对产品有100%的了解，还需要了解竞争对手的产品、功能，以及技术能力。同时，架构师做为产品团队和开发团队的沟通枢纽，需要协调好团队沟通、合作中出现的问题。当然第一的需要避免的发生的就是 “开发工程师拿刀砍了产品经理”！...

## 写在最后

也有人问我，架构师有什么优秀的品质。

第一，品质是人特有的特性，所以，好的品质并不需要区分架构师和非架构师。所以，那些你知道的优秀品质，对架构师统统适用。

第二，我怎么知道，我又不是架构师......

转自[大房说眼里的架构师](http://mp.weixin.qq.com/s?__biz=MzI4MjA4ODU0Ng==&mid=401373742&idx=1&sn=e27102eda726a2a56ee097013c2754ac).