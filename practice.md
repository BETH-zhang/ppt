title: 基于动态课件的题库交互设计
speaker: BETH
<!-- transition: slide
transition: slide1
transition: slide2
transition: slide3
transition: horizontal
transition: horizontal3d
transition: zoomin
transition: cards
transition: earthquake
transition: newspaper
transition: glue
transition: move -->
transition: kontext
files: /js/demo.js,/css/demo.css,/js/zoom.js
theme: green
usemathjax: yes

[slide]
# 基于动态课件的题库交互设计
<div class="avatar" style="font-weight: bolder;
  margin-bottom: 30px;">
  <img src="/img/2018beth.jpeg" alt="beth" style="width: 80px;height: 80px;min-width: initial!important;
  min-height: initial!important;
  position: initial!important;
  border-radius: 50%;
  display: block;
  margin: 0 auto;
  margin-bottom: 20px;" />
  张百鸽
</div>
`美小技术部－前端组`

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  padding: 10px 20px;    
  left: -10px;
  border: 1px solid #454E3C;
  background: #fff;color: #454E3C">基于动态课件的题库交互设计</div>
----

<div class="sanjiao-box">
  <a style="margin-top: 90px;"><h2 class="gray">动态课件</h2></a><br />
  <a><h1 class="gray2" style="font-size: 50px;">题(型)库</h1></a><br />
  <a><h1 class="blue2" style="font-size: 80px">交互设计</h1></a>
  <a><h1 class="blue3" style="font-size: 120px">项目设计</h1></a>
</div>
<style>
.sanjiao-box{
    border-bottom:solid 2px #454E3C;
    width:600px;
    height:600px;
    margin: 0 auto;
    box-sizing: border-box;
    position: relative;
}
.sanjiao-box:before,
.sanjiao-box:after{
    content:"";
    display: block;
    width:600px;
    height:600px;
    box-sizing: border-box;
    position: absolute;
}
.sanjiao-box:before{
    border-left:solid 2px #454E3C;
    transform-origin: left bottom;
    transform: rotate(30deg);
}
.sanjiao-box:after{
    top: 0;
    border-bottom:solid 2px #454E3C;
    transform: rotate(60deg);
    transform-origin: right bottom;
}
</style>

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  left: -10px;
  border: 1px solid #454E3C;
  padding: 10px 20px;
  background: #fff;color: #454E3C">初级版本的动态PPT</div>
## 初级版本的动态PPT

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  padding: 10px 20px;    
  left: -10px;
  border: 1px solid #454E3C;
  background: #fff;color: #454E3C">动态课件近况</div>
| | 课中 | 课后 |
:-------|:------:|:------:|
| 内容 | 新体系：Level1-5<br /> 旧体系：Level1-3 | 新体系：Level1-5 |
| 数量 | Level1-3: 86 × 4 <br />Level3.5: 43 × 2 <br />Level4-5: 86 × 4 | 774 |
| 进度 | 364 | 0 |
| 形式 | 动态PPT | H5 |
| 部门 | 内容，美术 | 内容，美术，技术 |
| 规划 | 3 ＊ 3 | 2 |

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  padding: 10px 20px;
  left: -10px;
  border: 1px solid #454E3C;
  background: #fff;color: #454E3C">动态课件题(型)库</div>
<img src="/practice/tx.png">

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  left: -10px;
  border: 1px solid #454E3C;
  padding: 10px 20px;
  background: #fff;color: #454E3C">交互设计有哪些</div>
| 设计要点 | 技术要点 |
:-------|:------:|
| 基础题型 | 交互动画(拖拽、连线、选择)、过度动画(缓动函数) |
| 场景动画 | 二维动画、过度动画、帧动画、音视频交互 |
| 音乐盒 | 场景动画、音频字幕交互 |
| 游戏场景 | 交互动画、逻辑封装 |

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  left: -10px;
  border: 1px solid #454E3C;
  padding: 10px 20px;
  background: #fff;color: #454E3C">动画配置全览</div>
<img src="/practice/config.png">

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  left: -10px;
  border: 1px solid #454E3C;
  padding: 10px 20px;
  background: #fff;color: #454E3C">交互课件对接流程</div>
<img src="/practice/dj.png">

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  left: -10px;
  border: 1px solid #454E3C;
  padding: 10px 20px;
  background: #fff;color: #454E3C">项目设计(路由，公共组件)</div>
<img src="/practice/h5.png">

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  left: -10px;
  border: 1px solid #454E3C;
  padding: 10px 20px;
  background: #fff;color: #454E3C">项目展示-场景动画</div>
<img src="/practice/demo.png">

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  left: -10px;
  border: 1px solid #454E3C;
  padding: 10px 20px;
  background: #fff;color: #454E3C">项目展示-课后题型库</div>
<img src="/practice/demo1.png">

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  left: -10px;
  border: 1px solid #454E3C;
  padding: 10px 20px;
  background: #fff;color: #454E3C">项目展示-课后题型库</div>
<img src="/practice/demo2.png">

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  left: -10px;
  border: 1px solid #454E3C;
  padding: 10px 20px;
  background: #fff;color: #454E3C">拖拽题</div>
<img src="/practice/drag.png">

| 事件钩子 | 操作 |
:-------|:------:|
| @drop | 目标对象 |
| @dragover | 拖拽过程的监听 |
| @draggable | 设置可拖拽 |
| @dragstart | 拖拽对象 |

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  left: -10px;
  border: 1px solid #454E3C;
  padding: 10px 20px;
  background: #fff;color: #454E3C">SVG连线题</div>
<img src="/practice/svg.png">

<pre><code>
svg id=svg1 width=17px height=28px viewBox=0 0 17 28
    g stroke=none stroke-width=1 fill=none>
        path d=M15.4947761,26.642102 C5.97606002,17.8370152 1.58243698,9.02575278 2.31390694,0.208314697 id=Path stroke=#F60909 stroke-width=3

new Vivus(id, {duration: 100, type: 'oneByOne', start: 'inViewport'}
</code></pre>

[slide]
<div class="title" style="position: absolute;
  top: 0;
  left: 0;
  left: -10px;
  border: 1px solid #454E3C;
  padding: 10px 20px;
  background: #fff;color: #454E3C">升级版本的动态PPT</div>
## 升级版本的动态PPT

[slide]
<div class="avatar" style="font-weight: bolder;
  margin-bottom: 30px;">
  <img src="/img/2018beth.jpeg" alt="beth" style="width: 80px;height: 80px;min-width: initial!important;
  min-height: initial!important;
  position: initial!important;
  border-radius: 50%;
  display: block;
  margin: 0 auto;
  margin-bottom: 20px;" />
</div>
# 谢谢!

<style>
table tr>td:first-child, table th {
  background: #454E3C;
}
table tbody tr td {
  border: 0;
}
table {
  color: #454E3C;
}
slides > slide {
  background: #9dc46b;
  background-image: url('/practice/ww.png');
  background-repeat: no-repeat;
  background-position: bottom left;
}
slides > slide:nth-child(6n+1), slides > slide:nth-child(6n+2), slides > slide:nth-child(6n+3), slides > slide:nth-child(6n+4), slides > slide:nth-child(6n+5) {
  background: #9dc46b;
  background-image: url('/practice/ww.png');
  background-repeat: no-repeat;
  background-position: bottom left;
}
</style>