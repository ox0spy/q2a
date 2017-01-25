## 整体认识 (2小时)

- [web前端技能汇总](https://github.com/JacksonTian/fks)
- [Web前端开发技能图谱](https://github.com/TeamStuQ/skill-map/blob/master/data/map-HTML5.md)


## 开发者工具 (2天)

目的：1. 编辑器 2. 代码提示 3. 可以快速插入code snippet

自己从下面选一个，并自己搜索如何将它配置为前端开发工具。

- Sublime Text
- Atom
- WebStorm
- VIM


## 语言学习 (5周)

### HTML (1周)

- [HTML入门](http://study.163.com/course/introduction/171001.htm#/courseDetail)
- [HTML 教程](http://www.w3school.com.cn/html/index.asp)
- [奇舞前端特训营](https://t.75team.com/)
- [Periodic table of HTML elements](https://madebymike.com.au/html5-periodic-table/)

学习要求：

- 学会常用HTML元素如何使用，知道如何写form表单
- 对HTML语义化有点了解
- 学会在Chrome中查看页面源码，inspect具体元素
- 自己通过HTML完成该页面 <http://ife.baidu.com/2016/task/detail?taskId=1>

### CSS (2周)

#### 入门

学习文档：

- [CSS3](http://study.163.com/course/introduction/190001.htm#/courseDetail)
- [CSS入门教程](https://developer.mozilla.org/zh-CN/docs/Web/Guide/CSS/Getting_started)
- [CSS教程](http://www.w3school.com.cn/css/index.asp)
- [学习CSS布局](http://zh.learnlayout.com/)
 + [Flexbox，更优雅的布局](https://segmentfault.com/a/1190000002490633)
- Eric Meyer 谈 CSS(卷2)
- 精通CSS
- [CSS居中]
 + [CSS居中完整版](https://github.com/Erichain/css-center-complete/blob/master/README-ZH_CN.md)
 + [Seven Ways of Centering With CSS](http://thenewcode.com/723/Seven-Ways-of-Centering-With-CSS)
 + [CSS 居中大全](http://jinlong.github.io/2013/08/13/centering-all-the-directions/)
 + [总结一些DIV居中的方法](https://github.com/simaQ/cssfun/issues/3)
 + [CSS居中完整指南](https://www.w3cplus.com/css/centering-css-complete-guide.html)

最后的两本书做参考吧。

学习要求：

- CSS选择器
- 字体、文字、演示、背景设置
- 盒模型
- CSS常用布局：块布局、行内布局、表格布局、定位布局、弹性盒子(flexbox)布局
- 学会在Chrome中查看、修改元素的CSS设置
- 自己通过HTML + CSS完成该题目 <http://ife.baidu.com/2016/task/detail?taskId=2>
- 还有兴趣可以完成该题目 <http://ife.baidu.com/2016/task/detail?taskId=7>

#### 进阶

- CSS 预处理器
 + [浅谈 CSS 预处理器（一）：为什么要使用预处理器？](https://github.com/cssmagic/blog/issues/73)
 + [浅谈 CSS 预处理器（二）：如何快速上手？](https://github.com/cssmagic/blog/issues/74)
- [Web Fundamentals by Google](https://developers.google.com/web/fundamentals/)
- [浏览器的工作原理：新式网络浏览器幕后揭秘](https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/)

### JavaScript (2周)

学习文档：

- [JavaScript入门视频](http://study.163.com/course/introduction/195001.htm#/courseDetail)
- [JavaScript入门视频](http://www.imooc.com/learn/36)
- JavaScript精髓 (必看)
- JavaScript DOM编程艺术(第2版)
- [Mozilla JavaScript教程](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)
- ES6学习
 + [ES6入门](http://es6.ruanyifeng.com)
 + [ES6 resource](https://github.com/lenville/es6-resources/blob/master/zh-Hans.md)
 + [ES6 features](https://github.com/ES-CN/es6features)
 + [learn es2015](https://babeljs.io/learn-es2015/)
 + [ES6-for-humans](https://github.com/metagrover/ES6-for-humans)
 + [ES6-for-humans中文翻译](https://www.gitbook.com/book/imbubble/es6-for-humans/details/zh-CN-master)
- ESLint
 + [ecomfe ESLint wiki](https://github.com/ecomfe/fecs/wiki/ESLint)
 + [淺入淺出 eslint 與實作](http://denny.qollie.com/2016/07/11/eslint-fxcking-setup/)


注：

- ES6可能没有时间在这两周内学习，先知道它的存在和它的好处吧
- ES6是JavaScript新版本的语法，类似Java 8 和 Java的关系。
-  通过[Babel](https://babeljs.io)可以方便的使用新语法写代码，然后，打包工具结合`Babel`将代码转换成老版本的JavaScript语法
- 一般是在编辑器或者webpack等工具中配置好ESLint，编码、打包时都会对自己代码做检查了。(强烈建议配置ESLint，避免低级错误)

学习要求：

- 学习JavaScript基本语法
- 熟悉JavaScript数据类型
- 理解JavaScript中的this
- `undefined`, `null`, `NaN`, `''`, `[]`, `{}` 的布尔值是什么?
- `==`和`===`的差异是什么? 自己编码中请只用`===`
- 思考下JavaScript中Array和Object的差异
- DOM操作
- 事件处理
 + [JavaScript 和事件](http://yujiangshui.com/javascript-event/)
- [对浏览器的window有大概了解](http://www.w3school.com.cn/jsref/dom_obj_window.asp)
- setTimeout、setInterval、clearTimeout、clearInterval
- 简单看看BOM
- 完成
 + <http://ife.baidu.com/2016/task/detail?taskId=13>
 + <http://ife.baidu.com/2016/task/detail?taskId=14>
 + <http://ife.baidu.com/2016/task/detail?taskId=21>

## 调试 (2天)

- [Chrome devtools](https://developer.chrome.com/devtools)
 + [CHROME开发者工具的小技巧](http://coolshell.cn/articles/17634.html)
- [微信Web开发者工具](https://mp.weixin.qq.com/wiki/10/e5f772f4521da17fa0d7304f68b97d7e.html)

## 工具库、框架 (自己学习)

- JavaScript开发者库 (提高开发效率)
 + [jQuery](http://jquery.com/)
 + [backbone](http://backbonejs.org/)
 + [underscore](http://underscorejs.org/)
- CSS框架 (提高开发效率)
 + PC端：[Bootstrap](http://www.bootcss.com/)
 + [Ant Design](https://ant.design/)
 + [Semantic UI](http://www.semantic-ui.cn/)
 + PC端：[Element](http://element.eleme.io/#/zh-CN)
 + 移动端：[vux](https://vux.li/#!/)


开发框架:

- [Vuejs](http://vuejs.org.cn)
- [React](https://facebook.github.io/react/)
- [Weex](http://weex-project.io/)

## 打包工具 (自己学习)

- [webpack](https://webpack.github.io/)

## 编码规范

- [网易规范](http://nec.netease.com/)

## 技术blog

- [alloyteam](http://www.alloyteam.com/)
- [淘宝前端团队](http://taobaofed.org/)
- [奇舞团博客](https://75team.com/)
- [百度WEB前端研发部](http://fex.baidu.com/)
- [mxd tencent](http://mxd.tencent.com/)
