## 前言

前后端项目目前已经部署到线上环境，大家可以通过以下地址进行访问：

**「掘掘记账本」在线预览：** http://cost.chennick.wang

> 测试账号：admin，测试密码：111111。也可以自行注册使用。

**「掘掘记账本」前端代码开源地址：** https://github.com/Nick930826/juejue-vite-h5

**「掘掘记账本」后端代码开源地址：** https://github.com/Nick930826/jue-diary-server

#### 使用到的软件下载地址

- VSCode：[下载地址](https://code.visualstudio.com/)

- DBeaver：[下载地址](https://github.com/dbeaver/dbeaver/releases)

- Postman：[下载地址](https://www.postman.com/downloads/)


## 前端职业生涯中遇到的这些事儿

已经工作 1-3 年的前端同学，或多会少都会遇到一些问题，比如不知道自己还能学什么，每天像一只无头苍蝇一样，到处学一点。并且我相信，在你的微信公众号里也关注着不少前端相关的公众号，碎片化的知识充斥着你的微信，动则手写 Vue、React、吊打面试官等等。

![](https://s.yezgea02.com/1625812389992/WeChat63349df0b050f26d3734ba6e9c5e3b21.png)

打一枪换一个地，今天讲 `Vue`，明天讲 `React`，后天讲 `Webpack`，面试文章更是让人心生焦虑，因为你看完之后，发现自己原来还有这么多不会的知识点，补到什么时候是个头。

你若是有很强的总结归纳能力，将所有碎片化的内容规整出来，形成自己的一套知识体系，那么以这样的学习能力，大可自学，不必买教程。

**但是大部分人焦虑的原因**，归根结底还是因为自身的知识体系还不够完善，自身目前所处的高度还不够，导致看待问题的视野还比较模糊。所以，你需要对整个软件工程有一个全链路的学习，这样你的视野将升入新的高度，看待问题将不再局限于某个页面、用某个技术怎么实现。

我不敢保证，去学习 `Node.js` 这门技术，就能让你完全成为一个全栈工程师。但至少遇到问题，你思考问题的解决方案，不再局限于前端范畴，可以结合服务端的知识，去解决前端层面遇到的问题。

我认为，全栈工程师的定义是受到各方面因素影响的。

假如你在一个小厂工作，不限制你使用的技术，无论是用 PHP、Java、Node、Go、Python，只要你能一人或协同多人完成前后端的开发工作，那也是算一名全栈工程师，只不过这样的全栈工程师干的事情是比较杂的，甚至可以叫“全干工程师”。

如果你身在大厂，大厂的工作流程是非常规范及专注的，此时你利用自己的专业知识，去帮助团队在前后端衔接、项目发布持续集成、错误监测工具、脚手架的搭建、公用组件私有化等等方面提高工作效率，那你也可以成为一名全栈工程师。

#### 例子1

我现在有一个想法。我是一个爱看技术文章的勤奋少年，每天早上打开电脑会先去掘金、CSDN、思否等技术平台阅读当天最新的文章，并且将一些好的文章收藏到浏览器的收藏夹里吃灰。但是每天都要打开这些不同的网站，非常麻烦，我想做一个聚合页面，将诸如上述平台的当天最新文章收集到一个网页中，并且要有用户权限，可以收藏文章。

此时就要用到了 `Node` 的爬虫知识，可以利用 `puppeteer` 无头浏览器，获取到相应的网页，并拿到 `dom` 节点，通过 `cheerio` 插件将 `dom` 节点转化为，可通过 `jQuery` 操作的方法。获取到文章标题和详情链接，将数据存入 `MySQL`。利用 Node 抛出接口，浏览器通过 API 接口，获取存储在 `MySQL` 中的数据。

#### 案例2

Web 网站做得多了，想换换技术栈，学习用 `React Native` 做 `App` 应用。于是乎，本小册开发的这套服务端接口，便能派上用场。甚至可以将接口数据，对接到小程序里，实现一套服务端接口多终端使用，不用再用 `Mock` 数据去填充内容。

> 上述例子想告诉大家，有全栈能力的你，可以实现很多，你以前想实现，却不能实现的想法。

## 为什么是 Node

为什么要选择 `Node` 进入全栈开发呢？很简单，作为前端，我们最熟悉的就是 `JS`，而 `Node` 赋予 `JS` 一些系统级的能力，这让我们学习 `Node` 时，不用再重新学习一门新的语言，只要你会 `JS`，结合本小册文档，以及合理的运用搜索引擎，你就能很好的入门 `Node`。

**Node 能做什么有趣的事情**

- 爬虫

- 工具

- 脚本

- 硬件

- 中台

- 通信

**Node 的就业情况**


![image.png](https://p1-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/cc81b3109f0b4ea1b74b0d365dc7c741~tplv-k3u1fbpfcp-watermark.image)

> 数据来自BOSS直聘。

无论是实习还是社招，`Node` 在行业的需求，以及薪资的水准，都是在普通前端之上的。你可以说我很庸俗，但是社会便是如此，你的付出和你的收获在一定程度上是成正比的。所以，现在就开启你的 `Node` 之旅，这可能会为你后期的职业生涯添上浓墨重彩的一笔。

## 小册设计思路

小册目的很明确，带一部分前端，从纯前端慢慢转变为伪全栈。为什么说是「伪全栈」呢？因为课程的深度不会涉及太多的性能相关的知识，如多集成、高并发、缓存优化、多进程部署之类的问题。这些都是需要你在课后自己去实践学习的内容。

> 如果真的有通过学习一门课程就变成大神，希望知道的同学，把这门课程推荐给我，我也想学。

先带大家拿起板砖🧱 ，敲开全栈的大门。知其然，而后使其然。

我们将会学习掌握下图流程：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/7b61a509885e41fbba4d955933907797~tplv-k3u1fbpfcp-zoom-1.image)

**需求分析**

项目的逻辑梳理，目的是为了下一步数据库设计做准备，需求分析和数据库设计其实是同步的，需要一边分析，一边设计。

**数据库设计**

本课程采用数据库为 `MySQL`，并且使用更加人性化的可视化工具 [DBeaver](https://dbeaver.io/)，更易于新手上手操作数据库。数据库的作用说简单了，就是为了存储数据，至于用什么技术，不必太过于拘泥，你也可以选择 `MongoDB`。

可视化界面如下：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/3705d4385742472f926205780ed4d5bb~tplv-k3u1fbpfcp-zoom-1.image)

**服务端接口编写**

本课程采用 `Node` 的上层架构 [Egg.js](https://eggjs.org/zh-cn/)，它是由阿里研发维护的，并且是基于 `Koa` 开发，有着高度可扩展的插件机制，很多需求我们可以通过插件的形式来实现，大厂的使用率也很高，文档相对国人友好，学习成本较低。

这里有一份前端早早聊大会公开的各大公司团队的[技术选型](https://www.yuque.com/zaotalk/team/st#6edd)，可以看到 `Node` 这块技术栈，使用 `Egg.js` 的公司占不小的比例。并且大厂都会有自己的前端基建，多数情况下也是采用的 `Egg.js` 作为基础 `Node` 框架。

既然大厂都在使用 `Egg.js`，想要获得更强的竞争力，你需要好好地学习它。

我所在的公司也不例外，包括海报生成、二维码生成、截图服务、静态资源 `CDN` 服务都是基于 `Egg.js` 开发的。


**前端开发**

前端部分采用目前大厂最爱的 `React`，全程使用 `React Hook` 的形式编写。由于咱们做的是记账本，属于金融类项目，所以本小册采用的是 [ZarmUI](https://zarm.gitee.io/#/) 作为组件库。组件库的使用需要根据项目而定，比如你开发的是 `toB` 的管理后台类项目，建议采用 [Ant Design](https://ant-design.gitee.io/docs/react/introduce-cn)。

脚手架采用的是 `Vite2.0`，它在开发模式下的冷启动，让你真正体验到秒更新的快感。我认为 `esm` 的模块化规范会是未来的趋势，趁早学习，占据主动。

后续的章节会对 `Vite` 做一个详细全面的分析。

最终会带大家开发出一个 `toC` 项目，如下图所示：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/6bcfa727648c4c73be85524e8b028550~tplv-k3u1fbpfcp-zoom-1.image)

**部署上线**

服务端的部署会教大家如何在服务器环境下安装 `MySQL`，前端和后端的代码，会通过 `pm2` 完成自动化部署，部署线上的前提条件是，需要你有一台云服务器。

## 适宜人群

**1、前端职业生涯前期，遇到学习瓶颈的同学。**

- 局限于前端的知识体系，会让你的思路也同样局限于前端的领域，拓展你的知识面，可以让你对整个技术的认知进入新的高度。

**2、在校学生，希望通过开发实战项目，完成毕设的同学。**

- 本项目带大家从 0 到 1 开发出一个完整的前后端项目，有助于即将毕业的同学很好的理解整个项目的开发过程，在写论文的时候，也能游刃有余。

**3、想通过学习 `Node`，拓展技能树，升职加薪的同学。**

- 多数在小厂做前端开发的同学应该有所体会，一直都是做一些不那么锻炼技术的后台管理系统。这些技能树可能不能很好地支撑你的涨薪诉求，入门 `Node` 后，你可以做一些提高开发效率的工具，帮助你获得更好的升职加薪的机会。

**4、想开启[「远程工作」](https://eleduck.com/)的同学。**

- 远程工作，很多时候需要你既会前端，又得回后端，因为雇佣者开发成本有限，需要开发人员的技能树尽可能的多。

## 我的职责

我并不是大佬，我只是一个，处在这个内卷的 IT 大环境下，不得不埋头向前的普通前端。相信和我一样的普通前端是占多数的，没有过人的天分，靠的多是自己的自觉和自律。职业生涯是漫长的，希望我能陪你走过这漫长职业生涯中的一小段。用我喜欢的一句话结尾。

> “以大多数人的努力程度之低，根本轮不到拼天赋。”

## 总结

风里雨里，我在交流群等你。