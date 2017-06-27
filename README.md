
## HTML
#### 书籍：
- [HTML5秘籍](https://book.douban.com/subject/11610880/) 
- [HTML5 Canvas核心技术](https://book.douban.com/subject/24533314/)

#### 问题：
- 浏览器渲染原理
- local stroage / session stroage / cookie / session
- 离线应用 & 本地化
- Web Worker
- websoket
- 前端路由实现（histroy api / hash tag）
- [async vs defer attributes](http://www.growingwiththeweb.com/2014/02/async-vs-defer-attributes.html)





## CSS
#### 书籍：
- [精通CSS](https://book.douban.com/subject/4736167/)

#### 问题：
- 基础
  - 两栏、三栏自适应布局
  - 保持容器宽高比（rem/em/vh/vw/padding）
  - 水平/垂直居中
  - [流体特性和BFC](http://www.zhangxinxu.com/wordpress/2015/02/css-deep-understand-flow-bfc-column-two-auto-layout/)
  - 浮动和清除浮动
  - 盒模型（低版本IE），border-box
  - 实现三角形、1/4圆形
  - [字号与行高](http://www.renfed.com/2017/06/13/font-size-line-height/)
  - 实现百度图片每列等宽

- 栅格
  - [使用Flexible实现手淘H5页面的终端适配](https://github.com/amfe/article/issues/17)
  - [Bootstrap 栅格系统的精妙之处](http://get.ftqq.com/6195.get)

- 动画
  - CSS、JS动画渲染原理、性能比较
  - [CSS Animation性能优化](https://github.com/amfe/article/issues/47)
  - [SVG 新司机开车指南](https://zhuanlan.zhihu.com/p/25016633)
  - [贝塞尔曲线扫盲](http://www.html-js.com/article/1628)






## JavaScript
#### 书籍：
- [你不知道的JavaScript（上卷）](https://book.douban.com/subject/26351021/)
- [你不知道的JavaScript（中卷）](https://book.douban.com/subject/26854244/)
- [JavaScript设计模式与开发实践](https://book.douban.com/subject/26382780/)
- [深入浅出React和Redux](https://book.douban.com/subject/27033213/)

#### blog: 
- [ECMAScript 6 入门](http://es6.ruanyifeng.com/)

#### 问题：
- ECMAScript 6
  - 有哪些新特性
  - 箭头函数this、arguments
  - Iterator与for...of关系（symbol.iterator）
  - Promise原理，race/all方法
  - generator与async
  - Proxy如何监测数组下标变动
  - Class与单例
  - module与commonjs区别

- JS基础
  - 闭包产生原因
  - [js实现继承的几种方式](https://segmentfault.com/a/1190000004730936)
  - [图解Javascript上下文与作用域](http://blog.rainy.im/2015/07/04/scope-chain-and-prototype-chain-in-js/)
  - [Javascript 中 == 和 === 区别](https://www.zhihu.com/question/31442029)
  - [Promise的队列与setTimeout的队列有何关联](https://www.zhihu.com/question/36972010)
  - [valueOf与toString](http://www.cnblogs.com/rubylouvre/archive/2010/10/01/1839748.html)
  - 手动实现bind
  - 判断一个对象是数组、类数组转数组、求交集并集
  - ECMA标准
  - instance of 原理

- 框架 
  - [Vue.js 源码学习](http://jiongks.name/blog/vue-code-review/)
  - [Vue对比其他框架](http://cn.vuejs.org/v2/guide/comparison.html)
  - [剖析Vue原理&实现双向绑定MVVM](https://segmentfault.com/a/1190000006599500)
  - [解析vue2.0的diff算法](https://github.com/aooy/blog/issues/2)
  - 大型单页面应用优化

- 设计模式
  - 单例、策略、代理、迭代器、发布-订阅、装饰者...





## Node.js
#### 书籍：
- [深入浅出Node.js](https://book.douban.com/subject/25768396/)

#### blog: 
- [Node.js 包教不包会](https://github.com/alsotang/node-lessons)
- [饿了么大前端 Node.js 进阶教程](http://cnodejs.org/topic/58ad76db7872ea0864fedfcc)

#### 问题：
- Node模块机制原理
- 垃圾回收机制
- 异步 & 异步编程
- 前后端编程区别





## 网络
#### 书籍：
- [HTTP权威指南](https://book.douban.com/subject/10746113/)
- [图解HTTP](https://book.douban.com/subject/25863515/)

#### 问题：
- HTTP
  - URI、方法、状态码、部首
  - [Web缓存机制](http://www.alloyteam.com/2012/03/web-cache-1-web-cache-overview/)
  - HTTPS原理（握手、非对称/对称加密）
  - [HTTP2.0的奇妙日常](http://www.alloyteam.com/2015/03/http2-0-di-qi-miao-ri-chang/)
  - 用 fiddler 捕获 https 请求

- TCP
  - TCP三次握手、四次挥手

- 安全
  - [XSS 与 CSRF](https://blog.tonyseek.com/post/introduce-to-xss-and-csrf/)
  - SQL注入

- 跨域
  - [Web开发中跨域的几种解决方案](http://harttle.com/2015/10/10/cross-origin.html)

- CDN
  - [CDN的作用与基本过程](http://blog.csdn.net/lihao21/article/details/52808747)





## 工程
- 性能优化
  - [阿里无线前端性能优化指南](https://github.com/amfe/article/issues/1)

- 模块化
  - [浅谈前端模块化](http://imweb.io/topic/55994b358555272639cb031b)
  - 模块加载器加载原理

- 构建工具
  - [webpack指南](https://doc.webpack-china.org/guides/get-started/)
  - [webpack原理与实战](http://imweb.io/topic/59324940b9b65af940bf58ae)
  - [webpack 热加载原理探索](http://shepherdwind.com/2017/02/07/webpack-hmr-principle/)
  - [FIS3工作原理](https://fex-team.github.io/fis3/docs/build.html)
  - webpack VS FIS

- 包管理
  - [Yarn vs npm](http://web.jobbole.com/88459/)





## 算法
- 冒泡
- 快排
- 堆排
- 归并
- 深度/广度优先遍历
- 二叉树遍历

