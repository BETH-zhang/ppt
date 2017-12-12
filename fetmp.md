title: 前端开发那些事儿
speaker: BETH
transition: slide3
files: /js/demo.js,/css/demo.css,/js/zoom.js
theme: pick

[slide]
# ![前端开发](/fe/1.png)
<div class="avatar">
  <img src="/img/beth.png" alt="beth" />
  张百鸽
</div>
`美小技术部－前端组`

[slide]
* 前端发展史
* 前端框架
* 开发技能
* 面试中，必考察的点

[slide]
<div class="title">前端发展史</div>

### 从静态走向动态
* 1994 前端起点(Web 1.0时代)
  10月13日 网景推出了第一版Navigator
  Tim Berners－Lee 创建W3C，Tim基友发布CSS
  Rasmus Lerdorf 动态Web网页设计的服务端脚本PHP(Personal Home Page)诞生
* 1995 网景推出JavaScript－实现客户端计算任务
* 1996 微软推出了iframe标签－实现异步的局部加载
* 1999 W3C发布第四代HTML标准
  微软推出用于异步数据传输的ActiveX
  各大浏览器厂商模拟实现了－XMLHttpRequest－Ajax诞生
* 2005 谷歌利用Ajax技术打造Gmail和谷歌地图之后－Ajax大受关注
 （进入Web2.0时代－－前端的第一次飞跃）
* 2006 XMLHttpRequest被W3C正式纳入标准（新浪、搜狐、网易、腾讯、淘宝）

[slide]
<div class="title">前端发展史</div>
![Web2.0](/fe/2.png)

[slide]
<div class="title">前端发展史</div>

### 从后端走向前端
* 后端主导－DOM操作（2005年之前，程序员，不区分前端和后端）
* 2006 John Resig发布了JQuery
  灵活的DOM操作
  优雅的语法、符合直觉的事件驱动
  极易上手，基于jQuery插件构成了庞大的生态系统
  （之前的前端不叫前端，工作比较简单，一般都是一个人前后端都开发；或者设计师边设计，边切图－网页设计师－美工）
* 制约Web开发从后到前的因素很简单，前端很多事情干不了，也干不好
  原因：浏览器性能弱，标准化程度低，IE市场份额大（ugly，buggy）
* 2008 谷歌V8引擎－现代浏览器的崛起终结了微软的垄断时代
  前端计算能力过剩

[slide]
<div class="title">前端发展史</div>
* 2009 标准组织发布第五代JavaScript（ES5）（前端开发工程师）
  前端装备整体提升，如同改革开放进入一个目不暇接的新时代
  AngularJS诞生
* 2010 backbone诞生
* 2011 React,Ember诞生
* 2014 Vue.js诞生－前后端分离大势所趋
  第五代HTML标准发布
  H5-浏览器厂商主导，与W3C合作制订的一整套Web应用规范（新的岗位H5前端开发工程师）

[slide]
<div class="title">前端发展史</div>
![前端开发](/fe/3.png)

[slide]
<div class="title">前端发展史</div>

### 从前端走向全端
* 2007 第一代iphone发布
* 2008 第一台安卓手机发布（移动端的发展进程和PC的历史如出一辙）
  Native App的天下(原生)
  浏览器试图取代操作系统的篡位之心从未消减
  Web App太多好处（无需开发两套版本，无须安装，无须手动升级，无须审核，最大的是降低成本）
  Web App太多问题（H5几大API：Geolocation API、Vibration API、Luminosity API、Camera API）
  性能差，是Native App还能作为主流存在一段时间的重要原因
  Hybrid，nw，Electron，react native，weex，以及半路杀出来的微信小程序－都是在想能方面向Native靠近的尝试

[slide]
<div class="title">前端发展史</div>
* 2009 Ryan Dahl发布了node（node基于V8引擎的服务端JavaScript运行环境，相当于一个虚拟机，js在服务端语言中有了一席之地）
 （前端的第二次飞跃）意味着JavaScript走出浏览器的藩篱，迈出了全端化的第一步
* 阮一峰说：未来只有两种软件工程师：端工程师（手机端，PC端，TV端，VR端。。。），云工程师
* （前端，后端，移动端，PC端（无处不见JS的存在）-游戏

[slide]
<div class="title">前端框架</div>
* 模版引擎： Ejs、Pug、Underscore.template、NodeTpl、artTemplate、juicer(node),Django(python)等
* UI库：Ant Design、Material UI、Bootstrap、We UI、Lay UI、Amaze UI、JQuery UI、自造UI等
* CSS库：SASS、LESS、CSS3、CSS Modules等
* JS库(统一接口封装)：JQuery、Zepto、requirejs、backbone.js、d3.js，Sea.js/KISSY（阿里系），Pomelo（网易系），fis/esl（百度系），JX/MT/FrozenUI（腾讯系）等
* 前端框架(具有特定的业务场景)：AngularJS、React、Vue、React-Native、Ionic,Walle(阿里系)等
* 构建工具：Webpack、Gulp、Grunt等
* IDE工具：VS Code、chrome浏览器、chrome开发者工具、翻墙工具等

[slide]
# 只有永远的类库，没有永远的框架

[slide]
<div class="title">开发技能</div>

### 中级前端开发工程师
* HTML－HTML5新规范（可以拆除几个分支）
* CSS－CSS3，以及SASS，或者LESS-页面布局，盒模型等
* 原生JS－原型链，DOM事件，面向对象，this关键字等
* 熟练使用第三方框架，理解框架实现的原理
* 网络层面，HTTP协议
* 能够进行插件开发，组件开发

[slide]
<div class="title">开发技能</div>

### 高级前端开发工程师
* 能够自己开发JS库
* 精通框架底层原理
* 能够实现高复用性，高性能的项目

[slide]
<div class="title">开发技能</div>

### 全栈开发工程师
* 测试类，实现前端的自动化测试和集成测试
* 通信类，跨域通信，接口通讯
* 前端安全类，XSS，CSRF
* 效能类，页面性能，项目优化
* 服务端，熟悉使用node作为后端服务（node，python，php）

[slide]
<div class="title">面试中，必考察的点</div>
作为一面，二面的面试官

* HTML－H5规范，HTML页面渲染原理
* CSS－CSS3属性，SASS和LESS区别，布局，盒子
* js基础－数据类型，this，闭包，继承
* js进阶－技术栈、第三方框架实现原理，使用的注意事项，React Diff算法,ES6和ES5对比优劣
* js高级－实现一个高难度的demo，算法
* 网络类-HTTP协议，HTTP状态码，HTTP请求头
* 通信类－跨域，跨域的解决方案
* 效能类－性能优化，函数优化，代码优化，浏览器
* 项目经验－做过的最复杂的模块或功能
* 工作流－了解个人开发习惯，git的使用，构建工具的使用

[slide]
### 从前端走向全栈

* 优秀的前端工程师招聘难度越来越大
* 全球架构师峰会-阿里菜鸟高级前端技术专家－银鹏提出
`全栈计划:Let's Full Stack全栈是一种“创业精神”`

[slide]
# ![前端开发](/fe/1.png)
# 谢谢!
