### 个人名片

|姓名|GitHub|Blog|mobile|email|学校|专业|学历|
|-|-|-|-|-|-|-|
|孙焕然|[@abbshr](http://github.com/abbshr)|[DigitalPie](http://digitpie.cf)|18704624517|abbshrsoufii@gmail.com|哈尔滨工业大学|软件工程|本科|

### 能力概述

#### 语言
擅使JavaScript/**Node.js**/CoffeeScript, 也用Ruby、Lua、C做过开发。

学过Lisp, 了解lambda演算等一些函数式编程的思想及理论基础。

正在**Rust**和**Nim**上投入学习。

#### Web 技术
在 Web 技术上，能够熟练运用Web技术、Hack手段以及多种JavaScript奇技淫巧。

完整阅读过RFC 6544 WebSocket Protocol, 实现了一个WebSocket库, 并在实验室和俱乐部做过一期关于RealTime Web的技术分享讲座。对计算机网络感兴趣, 曾实现过Node.js版的GBN协议模型和停等协议, 对WebRTC技术有一定了解。

阅读了Connect框架的源码。能使用Express、LoopBack、Sinatra、Connect、Koa、cheerio、libgit2等库和框架构建应用或工具。

用过 Openresty，并基于它给创业公司开发过一个简易的微服务网关。

#### 基础技术
目前正在涉足分布式领域，对分布式系统相关的技术与理论很有兴趣。学习并研究过数据一致性相关算法，数据分区、存储、通信、健康监测、流量控制等相关技术，阅读过关于 anti-enproy gossip 的论文。并且本科毕业设计就是设计并实现一个分布式API网关，其中自己实现了同步算法、负载均衡、底层k-v数据存储、节点健康探测、集群自治、多模式限速、插件系统等。

了解并能熟练运用基本的算法和数据结构于实际开发中，能够做适当优化以适配需求。

数据存储产品上，经常使用 Redis、LevelDB，不过更倾向于学习它们，编写完善自己的存储系统。

读过Node.js和libuv部分源码, 清楚其主要实现机制, 如Node启动, 流机制, 模块加载, 事件循环, 事件触发等等, 修改编译过一个自定义版的Node.js.

#### 工作 & 效率
熟悉Linux大部分命令、系统/网络管理技术和Bash脚本编程. 懂得Git底层工作机制, 并能熟练使用Git进行版本控制以及应用开发.

除此之外, 完整阅读了比特币创业公司bitpay的开源项目insight-api源码, 并贡献了代码, 做过BitCoin BlockChain的数据可视化与分析。

### 开源产品:
* JavaScript & Node.js  
	- Archangel: 一个分布式 API 网关，由 Kodiak、Leviathan、Nero 三大系统组成。
	- [Leviathan](https://github.com/abbshr/Leviathan): 分布式数据存储系统。
	- [Nero](https://github.com/abbshr/Nero): API 网关系统。
	- [hive-fs](https://github.com/abbshr/hive-fs): 基于索引和连续块偏移的 K-V 存储引擎。
	- [parted](https://github.com/abbshr/parted): 基于一致性 Hash 的负载均衡器。
	- [leviathan-gossip](https://github.com/abbshr/leviathan-gossip): Leviathan 中使用的 gossip 协议库。
	- [RocketEngine](https://github.com/abbshr/RocketEngine): 一个完整的超轻量级Node.js WebSocket库, 无第三方模块依赖, 使用简单, 并且提供了Socket.IO尚未支持的流式API和二进制流传输。被用于Yinle.me的重构以及几个外包项目中。
	- [execq](https://github.com/abbshr/execQ): 曾用于RocketEngine库内部,  解决异步工作流次序问题.
	- [event.js](https://github.com/abbshr/event.js): 用于RocketEngine前端库内部, 在浏览器端实现异步操作的Pub/Sub观察者体系.
	- [node-rate-limter](https://github.com/abbshr/node-rate-limiter): Node分布式限流器
	- [node-adt](https://github.com/abbshr/node-adt): 将JSON数据转换成Tree ADT，增强对JSON数据操纵能力。
	- [node-lock](https://github.com/abbshr/node-lock): 另一种思路实现Node多进程下互斥锁机制.
	- [read.i](https://github.com/abbshr/read.i): 解决Node.js中异步标准I/O的麻烦,方便终端输入
	- [colorlogger](https://github.com/abbshr/colorlogger): 实现彩色终端日志的输出与保存
	- [Lotterior](https://github.com/abbshr/Lotterior): Node/Coffee抽奖机，较高的可配置性
* Lua
    - [openresty-lua-plugin-loadsys](): 基于openresty的简易版 API 网关（以插件功能为主）。
* Ruby
    - [gitdb](https://github.com/AustinChou/Git-Contacts/tree/git-repository): 封装了Git的底层操作，是Git-Contacts的源动力.
* CSS & HTML
    - [inkiron](https://github.com/abbshr/inkiron): 暑期实训项目写的类flat UI风格的前端CSS框架.

### 完整作品

- 完整web应用 & 后台服务:
	* [Yinle.me](https://github.com/abbshr/Yinle.me-architecture): 私有项目. 一款Node.js编写的面向校园的云打印服务, 曾得过IBM暑期夏令营的创新大赛二等奖. 经历了两次重构，重构使用了LoopBack框架，
		并扩展了扫码打印，打印机群管理，资源共享，在线支付等功能.
	* [ctheyvs](https://github.com/abbshr/ctheyvs): 一个外卖比价器. 综合运用了爬虫, 前端hack, 集群, 动态规划, 字符串模糊匹配算法等技术与理论.
	* [Git-Contacts](https://github.com/abbshr/Git-Contacts): 使用Git特性开发的通讯录共享服务, Ruby开发.
	* [Hugo](https://github.com/abbshr/lbs-app): 一个基于AMap地图的信息分享应用，使用CoffeeScript，RethinkDB，thinky，SemanticUI以及Angular.js构建.
- 数据可视化:
    * [env.BTC](https://github.com/abbshr/env.BTC): 基于开源项目insight/insight-api开发的比特币区块链数据可视化与分析系统, 未完工.
- 密码学研究:
	* [encryp2p](https://github.com/abbshr/encryp2p): 参考HTTPS的安全模型, 由Ruby编写的P2P文件加密共享程序, 实现了来源可靠性, 信息加密性以及完整性验证.

### 实习经历

+ (2015.7.24 - 2015.10.31)阿里云-数据事业部-数据引擎-Node.js开发  
	负责应用服务中API Gateway开发, 维护与优化, 处理并输出整个集团各部门产生的以及需要的数据. 为高负载高并发场景(如:天猫双十一)高效稳定服务于上层各个业务。达成成就:  
    - 做集群的配置服务性能优化, 上线了重构的API Gateway的配置服务器模块.
    - 设计开发并上线了API Gateway针对集群精准限流的Web中间件, 在保证高性能的情况下进行整体流量控制.
    - 设计开发了集群的弹性限流功能.
    - 修复业务代码打包系统中的bugs.
    - 写了几个库: node-adt, node-lock, node-rate-limit, 已经被多个内部项目使用.
    - 完成配置服务器与底层存储系统的对接.
    - 重构了API Gateway的大部分代码.
+ (2015.11.2 - 2016.1.11)UPYUN-应用开发-Node.js开发  
    在应用开发组做Node.js基础技术，实习期间完成了:  
    - 内部Node.js mysql ORM的重构, 开发, 编写测试以及后期维护.
    - 设计实现了基于sliding-window的高性能精准限流算法portal-throttle.
    - 搭建并维护基于ELK的数据处理平台.
    - 开发维护内部Node.js DNS库node-dig.
    - 搭建维护gitlab-ci系统.
    - 完善了内部开发/系统维护文档.
+ (2016.1.13 - 2016.2.1)阿拉丁众合信息科技-DevOps/BackEnd
    负责 API 网关的调研、设计、开发、维护等工作以及 Openresty 的维护，插件的开发。期间以 Lua 开发为主，达成成就：  
    - 技术选型
    - 完善运维文档
    - 开发插件
    - openresty 运维
    - 搭建维护日志系统
