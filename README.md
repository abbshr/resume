ran's Profile
===

### 申请职位
Node.js工程师

### 个人名片
+ 姓名: 孙焕然
+ 学校: 哈尔滨工业大学
+ 专业: 软件工程
+ 学历: 本科
+ HIT FoOTOo实验室(IBM技术中心)成员
+ GitHub: @[abbshr](http://github.com/abbshr)
+ Google+: @[Ran Aizen](http://plus.google.com/u/+RanAizen)
+ Blog: http://digitpie.cf
+ mobile: 18704624517

### 能力概述
 
擅使JavaScript/Node.js, 对异步编程运用自如. 能够熟练运用Web技术、Hack手段以及各种JavaScript奇淫技巧, 从而有多种技术和手段从各种类型的页面中提取需要的数据和信息. 
常年工作于Ubuntu环境下, 熟悉Linux常规操作、系统管理技术和Bash脚本编程. 熟悉Git原理, 能熟练使用Git进行版本控制以及应用开发. 
热衷RealTime Web技术, 特别是WebSocket. 完整阅读过RFC 6544 WebSocket Protocol, 实现了一个WebSocket库, 并在实验室和俱乐部做过一期关于RealTime Web的技术分享讲座. 对计算机网络有所研究, 曾实现过Node.js版的GBN协议模型和停等协议. 
喜欢研究了解系统底层的技术, 阅读过实验室翻译的《Linux System Programming》, 对系统编程知识如Linux I/O技术内幕, 缓冲, 磁盘I/O以及流式I/O有一定的了解. 
读过Node.js和libuv源码, 清楚其实现机制, 如Node启动, 模块加载, 事件循环, 事件触发, 流机制等等, 修改编译了一个自定义版的Node.js.
除此之外, 也研究过BitCoin技术, 完整阅读了比特币创业公司bitpay的开源项目insight-api源码, 并贡献了代码, 目前正在做BitCoin BlockChain的数据可视化与分析.
在Web开发方面, 阅读了Connect框架的源码, 了解Express的中间件技术等内部实现.
在开发JavaScript全栈式Web应用时, 接触到了NoSQL理论. 熟悉LevelDB、MongoDB、Redis。
平日比较倾向于自己写框架或库去解决开发中的问题. 因学习过JavaScript设计模式, 总想给应用设计合适的架构选择合适的模式. 擅于从旧的东西上重新挖掘可利用价值与可学习的东西.

### 工具
+ 框架&库: Express, Connect, React, cheerio, libgit2等
+ 编程语言: Bash, Ruby, C, Lua
+ 手边利器: Git, appfog, firebase, Chrome Dev Tool, Sublime Text

### 作品
+ 实现作品: 
  - 纯前端:
	    * [五子棋](https://github.com/abbshr/JSCode/tree/master/%E4%BA%94%E5%AD%90%E6%A3%8B): JavaScript写的五子棋小游戏
	    * [SFD抽奖机](https://github.com/FoOTOo/SFD2013-Harbin):为实验室承办的SFD活动制作的功能丰富的抽奖程序, JavaScript实现
	    * [FoOTOo page](http://footoo.github.io/): 为实验室编写的一套CSS theme.
  - 完整web应用:
	    * [BlogOS](https://github.com/abbshr/BlogOS): 基于Express框架和MongoDB数据库的微型论坛系统
	    * [TeamChat](https://github.com/abbshr/FoOTOoRTCA): 我的第一个实验室项目. 基于Socket.IO和Express的实时团队协作工具,但由于时间仓促,未实现全部功能.
	    * [Yinle.me](https://github.com/FoOTOo/Yinle.me): 私有项目. 一款Node.js编写的面向校园的云打印服务, 除后台使用了Express框架, 前台的UI和应用逻辑全为自己手写, 未借助任何库和框架. 我的第二个实验室项目.
	    * [ctheyvs](https://github.com/abbshr/ctheyvs): 一个外卖比价器. 综合运用了爬虫, 前端hack, 集群, 动态规划, 字符串模糊匹配算法等技术与理论.
	    * healthlink: 私有项目. 健康跟踪应用demo. 一个外包项目, 包括日常饮食记录的图表展示, 即时聊天等.
  - 后台服务:
	    * [hackhit](https://github.com/abbshr/hackhit): 模拟浏览器端登陆学校教务处,曾是一个课程表项目的模块.
	    * [Git-Contacts](https://github.com/AustinChou/Git-Contacts): 使用Git特性开发的通讯录共享服务, Ruby开发. 我和同学合作的第四个实验室项目.
  - 数据可视化:
	    * [env.BTC](https://github.com/abbshr/env.BTC): 基于开源项目insight/insight-api开发的比特币区块链数据可视化与分析系统, 我的第三个实验室项目, 尚未完工.

+ 个人开源框架/库:
  * JavaScript & Node.js
	    - [RocketEngine](https://github.com/abbshr/RocketEngine): npm模块. 一个完整的超轻量级Node.js WebSocket库, 无第三方模块依赖,使用简单,功能丰富.
	    - [wsframe](https://github.com/abbshr/wsframe): 从RocketEngine中分离出的WebSocket Frame解析器/生成器
	    - [execq](https://github.com/abbshr/execQ): npm模块. 用于RocketEngine库内部, 可以阻塞当前任务的,并在合适时候执行他们, 目的是处理异步工作流.
	    - [event.js](https://github.com/abbshr/event.js): 用于RocketEngine前端库内部, 一个在浏览器端实现异步操作的事件驱动编程框架,依照Pub/Sub观察者体系模式设计
	    - [read.i](https://github.com/abbshr/read.i): npm模块, 解决Node.js中异步标准I/O的麻烦,方便终端输入
	    - [colorlogger](https://github.com/abbshr/colorlogger): npm模块, 作为RocketEngine库的工具包, 实现终端日志的彩色输出与保存  
  * Ruby
	    - [gitdb](https://github.com/AustinChou/Git-Contacts/tree/git-repository): gem模块，封装了Git的底层操作，是Git-Contacts的源动力.
  * CSS & HTML
	    - [inkiron](https://github.com/abbshr/inkiron): 暑期实训项目写的类flat UI风格的前端CSS框架.
