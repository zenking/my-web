# 说明
学习 WEB 需要的内容整理，包括前端思想、框架、css、js（框架）、http协议等等 ……
欢迎 `fork` 后贡献 `PR` ，一起努力打造更好的 `web` 学习资料~

# HTTP 协议
## HTTP Response Code
- [理解HTTP/304响应](http://www.cnblogs.com/ziyunfei/archive/2012/11/17/2772729.html)  English version [Understanding HTTP/304 Responses](http://www.telerik.com/blogs/understanding-http-304-responses)

## HTTPS
什么是HTTPS？ [zh-wikipedia 超文本传输安全协议](http://zh.wikipedia.org/zh/%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%AE%89%E5%85%A8%E5%8D%8F%E8%AE%AE) （目前大陆已经被封需要翻墙才能阅读，可以阅读英文版[en-wikipedia HTTPS](http://en.wikipedia.org/wiki/HTTPS)）

微博[@BAIDU罗成](http://weibo.com/u/1822556675)的一篇文章 [中国互联网全站HTTPS的时代已经到来](http://blog.csdn.net/luocn99/article/details/39777707)对HTTPS的原理、遇到的问题、有哪些影响做出了介绍，比较容易理解。

百度在2015年3月份全站正式转入HTTPs，下面的几篇文章正是其运维团队的总结经验，很有阅读价值。
- [全站 https 时代的号角 : 大型网站的 https 实践系列](http://op.baidu.com/2015/04/https-index/)
- [大型网站的 HTTPS 实践（一）—— HTTPS 协议和原理](http://op.baidu.com/2015/04/https-s01a01/)
- [大型网站的 HTTPS 实践（二）——HTTPS 对性能的影响](http://op.baidu.com/2015/04/https-s01a02/)
- [大型网站的 HTTPS 实践（三）——基于协议和配置的优化](http://op.baidu.com/2015/04/https-s01a03/)
- [大型网站的 HTTPS 实践（四）——协议层以外的实践](http://op.baidu.com/2015/04/https-s01a04/)

#### 既然 HTTPS 解决了我们关注的隐私、安全问题，那么为什么这么少的网站使用呢？
- [Stackoverflow.com: the road to SSL](http://nickcraver.com/blog/2013/04/23/stackoverflow-com-the-road-to-ssl/) statckoverflow 的创始人解答，大型网站的转型需要众多依赖的组件、服务商都支持HTTPS，最关键的还是CA证书问题。
- [知乎-如何看待百度全站搜索进入 HTTPS 时代？](http://www.zhihu.com/question/28379088)


#### 业界的支持
- [HTTPS as a ranking signal](http://www.googlewebmastercentral.blogspot.ch/2014/08/https-as-ranking-signal.html) 2014-08 google宣布全站HTTPS化，并且调整page rank 算法，搜索中支持搜索 HTTPS 的站点。
- 2015-03 月份百度全站 HTTPS 化，并且在2015-05-25日宣布[百度开放收录https站点公告](http://zhanzhang.baidu.com/wiki/392)，从此百度也能搜索HTTPS的站点内容了。

#### 如何申请
- [https的免费申请流程](http://ljinkai.github.io/2015/06/30/https-2/)

## HTTP/2
- [Home page for http/2](http://http2.github.io/) http/2 协议官网发布网站，内容更新均在此发布
- [Http/2 wikipedia](http://en.wikipedia.org/wiki/HTTP/2) 维基百科 http/2 资料，很多参考连接
- [http2 详解（中文）](https://www.gitbook.com/book/ye11ow/http2-explained)， English version follow this [http2 explained](http://daniel.haxx.se/http2/)，详细讲述http/1.1 的各种不足以及http/2所有的各种优化等，值得一看。github地址为[http2-explained-chinese](https://github.com/ye11ow/http2-explained-chinese)

[@qgy18](https://twitter.com/qgy18)在他的小站中写了三篇对比 HTTP1 和 HTTP2 性能优化的文章，对比两种协议里面为了共同的浏览体验、性能所做出的不同的优化，值得看一看。同时，他的小站已经全面支持 HTTPS，赞一个！
- [HTTP/2 与 WEB 性能优化（一）](https://www.imququ.com/post/http2-and-wpo-1.html)
- [HTTP/2 与 WEB 性能优化（二）](https://www.imququ.com/post/http2-and-wpo-2.html)
- [HTTP/2 与 WEB 性能优化（三）](https://www.imququ.com/post/http2-and-wpo-3.html)

# 前端学习
- [前端学习路线图](https://github.com/unruledboy/WebFrontEndStack) 文章解释说明[Web前端开发大系概览 （前端开发技术栈）](http://www.cnblogs.com/unruledboy/p/WebFrontEndStack.html)
- [前端技能汇总 Frontend Knowledge Structure --github](https://github.com/JacksonTian/fks) 由阿里前端两位杰出的工程师维护的关于前端的知识图谱 [@JacksonTian](https://github.com/JacksonTian) [@jayli（拔赤）](https://github.com/jayli/)
- [Web前端知识体系大全](http://www.cnblogs.com/wangfupeng1988/p/4649709.html) cnblog 上的一哥们写的，挺全面的。
- [Web 基本法则-现代 web 开发最佳实践](https://developers.google.com/web/fundamentals/) google 官方现代多设备 web 开发指南，特别是针对pc web、移动端的设计原则实践，值得每个web开发人员仔细阅读。
- [前端代码规范及最佳实践](http://coderlmn.github.io/code-standards/) [Isobar公司](http://www.isobar.com/global/)的创意技术部（前端工程）开发web应用的规范，此连接为中文翻译版本，英文版本见 [github-isobar-idev](https://github.com/isobar-idev/code-standards)
- [前端开发-好习惯、用法](http://coderlmn.github.io/Front-End-Development-Guidelines/) 一些不错的建议，很多在前面的文章中也有描述。
- [比较全面的前端面试资料收集](https://github.com/hawx1993/Front-end-Interview-questions) 主要是原理层面，知识点的理解。
- [Front-end-Web-Development-Interview-Question](https://github.com/paddingme/Front-end-Web-Development-Interview-Question) 包含笔试题、面试题以及简历的一些技巧。
- [如何挑选适合的前端框架？](http://www.csdn.net/article/2015-05-11/2824656-fontend-Frameworks) Angular Js、backbone等各种各样的前端MVVM框架层出不穷，移动端友好、SEO 友好，面临这些需求，有哪些原则、挑战，如何筛选？去哪儿网前端架构师司徒正美分析了各主流行框架优劣点、适用场景，并针对不同规模的公司、项目给出了相应的前端技术选择方案。
- [浏览器缓存知识小结及应用](http://www.cnblogs.com/lyzg/p/5125934.html) 关于浏览器缓存，讲解的很清楚、细致。


## 开发调试
- Chrome开发者工具不完全指南 [基础篇](http://web.jobbole.com/82558/)、[进阶篇](http://web.jobbole.com/82562/)、[性能篇](http://web.jobbole.com/82576/)、[性能进阶篇](http://web.jobbole.com/82590/)、[移动篇](http://web.jobbole.com/82612/)、[插件篇](http://web.jobbole.com/82701/) 从头介绍如何使用 chrome 进行 web 开发中的调试工作，包括 source、console、性能、profile、移动端调试、常用插件等的介绍，适合想更全面的了解强大的chrome 工具的同学。
- [Collection of links to assist you in web design and development](https://github.com/noahbuscher/Inspire) 前端设计、框架工具、打包工具、团队协作等一些资料工具使用。


## javascript
- [MDN javascript资料](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript) firefox js 资料库
- [ECMAScript 6](https://zh.wikipedia.org/wiki/ECMAScript) 新一代的 javascript 标准，带来很多先进的理念和特性，查看阮一峰写的电子书《[ECMAScript 6入门](http://es6.ruanyifeng.com/)》进行学习，或者查看 mozilla 的系列文章《[ES6 In Depth Articles](https://hacks.mozilla.org/category/es6-in-depth/)》 中文翻译由CSDN极客头条[探秘ES6](http://www.csdn.net/tag/%E6%8E%A2%E7%A7%98es6/news)。
- [JavaScript Patterns Collection](http://shichuan.github.io/javascript-patterns/) js 的开发规模式或者说推荐的写法。

## html5
- [极客学院-h5学习计划系列视频](http://e.jikexueyuan.com/html5.html?hmsr=osc_word_html5_07.01)

# 性能优化

- [书籍：高性能网站建设](http://book.douban.com/subject/26411563/)，[高性能网站-Web开发者性能优化最佳实践](http://book.douban.com/subject/4719162/)
- [书籍：High Performance Browser Networking](http://book.douban.com/subject/25856314/) 全书以性能优化为主线，从TCP、UDP 和TLS 协议讲起，解释了如何针对这几种协议和基础设施来优化应用。然后深入探讨了无线和移动网络的工作机制。最后，揭示了HTTP 协议的底层细节，同时详细介绍了HTTP 2.0、 XHR、SSE、WebSocket、WebRTC 和DataChannel 等现代浏览器新增的具有革命性的新能力。（-豆瓣简介）
- [Web性能优化：What? Why? How?](http://www.cnblogs.com/dojo-lzz/p/4591446.html) 文章从`减少http请求`、`页面内优化`、`启用缓存`、`减少下载量`、`网络优化`等几个方面进行阐述如何让页面加载更快！
- [毫秒必争，前端网页性能最佳实践法则](http://www.cnblogs.com/developersupport/p/webpage-performance-best-practices.html)  从网页内容、服务器端、图片、cookie、css、js等角度阐述优化的实践内容。
- [Google - PageSpeed Insights规则](https://developers.google.com/speed/docs/insights/rules)
- [Yahoo - Best Practices for Speeding Up Your Web Site](https://developer.yahoo.com/performance/rules.html) ， [中文翻译](http://dudo.org/archives/2008051211216.html)
- [Web前端优化最佳实践及工具集锦](http://www.csdn.net/article/2013-09-23/2817020-web-performance-optimization) 对上两条 google 和 yahoo 理论的实践文章，并提供一些调试优化的前端工具。
- [网页性能管理详解-阮一峰](http://www.ruanyifeng.com/blog/2015/09/web-page-performance-in-depth.html) 详述页面加载的原理机制及优化场景。

## 工具利器
- [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) Google的工具很是方便，极力推荐。
- [阿里测](http://www.alibench.com/) 帮助分析排查页面的性能优化点
- [爱前端-前端测试服务](http://itest.aliyun.com/index.htm) UI自动化测试、多浏览器检测（js\css脚本错误等）、页面坏死链检测等，方便在多浏览器的兼容性测试过程中快速发现定位问题，节约时间。或者这个也不错[前端测试服务](http://fts.aliyun.com/index.htm?spm=0.0.0.0.IDYSmX)
- [阿里移动质量中心](http://mqc.aliyun.com/?spm=0.0.0.0.id9E8r) 安卓、ios、h5兼容性测试，可以很方便的适配多种安卓终端、ios的多个版本吧兼容性等，很是方便。
- [JavaScript 堆内存分析新工具 OneHeap](http://www.html-js.com/article/3091)、[OneProfile](http://www.html-js.com/article/3083)
- [web以及移动端安全测试工具-HiTest 安全测试服务](http://sts.aliyun.com/index.html?spm=0.0.0.0.boVYwN)

# 前后端交互
- [Rest - Representational state transfer](https://en.wikipedia.org/wiki/Representational_state_transfer) wikipedia 介绍，[中文在此](https://zh.wikipedia.org/wiki/REST)
- [阮一峰 - 理解RESTful架构](http://www.ruanyifeng.com/blog/2011/09/restful.html)
- [撰写合格的REST API：设计准则](http://mp.weixin.qq.com/s?__biz=MzA3NDM0ODQwMw==&mid=208060670&idx=1&sn=ce67b8896985e8448137052b338093e0) 从RFC一致性、接口的安全性、丰富的接口文档、访问限制等方面进行阐述，通俗易懂，很是推荐阅读。
- [Restful Api 安全设计参考](http://drops.wooyun.org/web/9737?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
- [Web 研发模式演变 - 为什么要进行前后端分离？](https://github.com/lifesinger/blog/issues/184) [@玉伯](https://github.com/lifesinger) 前端模块化开发[sea.js](http://seajs.org/docs/#intro)的维护者，推荐阅读。
- [基于NodeJS的前后端分离(Taobao UED)](http://ued.taobao.org/blog/2014/04/full-stack-development-with-nodejs/) 淘宝 @常胤  整理的对前后端交互的问题进行说明和提出解决方法，值得推荐阅读。


## 常用 CDN 服务
- [百度静态资源公共库](http://cdn.code.baidu.com/)
- [360 网站卫士常用前端公共库 CDN 服务](http://libs.useso.com/)
- [Bootstrap 中文网开源项目免费 CDN 服务](http://www.bootcdn.cn/)
- [CDN公共库-插件库](http://www.jq22.com/cdn/)
- [jQuery CDN](http://code.jquery.com/)
