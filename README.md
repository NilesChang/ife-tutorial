# Guide For Front-end Developers

本项目作为一份前端学习的指南，内容主要包括前端学习所包括的主要知识，例如HTML、CSS、JavaScript等基础内容，
还包括一些前端高级技术，例如常用的前端框架等。

## 0 Preface

### 0.1 常用的Web工具

- IDE: Sublime、WebStorm、Visual Studio Code、Atom
  - [Sublime常用配置技巧与常用插件](http://wwsun.me/posts/sublime-usage.html)
- [W3C：HTML规范验证服务](https://validator.w3.org)
- 浏览器兼容性查询：[Can I Use](http://caniuse.com/)
- 图像占位符服务：[placehold.it](http://placehold.it/)
- Web字体托管服务：[FontSquirrel](http://www.fontsquirrel.com/) | [Google Fonts]()
- Web颜色生成器：[coolors.co](https://coolors.co/)
- [跨浏览器测试工具modern.IE](https://www.modern.ie/zh-cn)
- [BootCDN: 稳定、快速、免费的开源项目 CDN 服务](http://www.bootcdn.cn/)

### 0.2 线上讨论

- Quora: [What are the best resources for learning JavaScript?](https://www.quora.com/What-are-the-best-resources-for-learning-JavaScript)
- [知乎中一些值得推荐的前端领域相关问答](http://www.zhihu.com/question/20246142)
- 知乎：[有哪些关于前端技术的推荐书籍](http://www.zhihu.com/question/19809484?rf=20315724)
- [前端知识体系](https://github.com/JacksonTian/fks)
- [JavaScript之路（包含大量学习资源）](http://jstherightway.org/)
- [一些前端面试题](https://github.com/h5bp/Front-end-Developer-Interview-Questions)

## 1 Primer

前端入门基础知识，通过一些书籍资料全面入门前端开发的基础内容。

### 1.1 阅读材料

- [Head First HTML与CSS（第2版）](http://book.douban.com/subject/25752357/) | [Codes](https://github.com/bethrobson/Head-First-HTML)
- [Head First HTML5 Programming（中文版）](http://book.douban.com/subject/19894872/) | [Codes](https://github.com/bethrobson/Head-First-HTML5)
- [HTML & XHTML: The Definitive Guide](http://book.douban.com/subject/2061604/)
- [MDN: HTML5开发指南](https://developer.mozilla.org/zh-CN/docs/Web/Guide/HTML/HTML5)
- [MDN: CSS文档](https://developer.mozilla.org/zh-CN/docs/Web/CSS)
- [CSS Pocket Reference](http://shop.oreilly.com/product/0636920015055.do)

### 1.2 HTML基础知识

- HTML元素
  - [HTML中的块元素与内联元素](http://www.w3school.com.cn/html/html_blocks.asp)
  - [The Difference Between "Block" and "Inline"](http://www.impressivewebs.com/difference-block-inline-css/)
  - [HTML void元素](http://ourjs.com/detail/531b2ce89144f4934f00000b)
  - [HTML列表元素：有序列表、无需列表、定义列表](http://www.w3school.com.cn/html/html_lists.asp)
  - CSS-TRICKS: [A Complete Guide to the Table Element](https://css-tricks.com/complete-guide-table-element/)
  - MDN: [使用HTML5音频和视频](https://developer.mozilla.org/zh-CN/docs/Web/Guide/HTML/Using_HTML5_audio_and_video)
  - [使用HTML5视频格式：mp4、webm、ogv](http://dwz.cn/2Ln8Jw)
  - [HTML5的视频格式之争](http://www.ruanyifeng.com/blog/2010/05/html5_codec_fight.html)
  - [区分视频编解码器codec和视频容器container](http://blog.csdn.net/defonds/article/details/17717643)
- [HTML字符实体](http://www.w3school.com.cn/html/html_entities.asp)
- 字符编码
  - [HTML5 字符编码](http://wiki.jikexueyuan.com/project/html5/char-encodings.html)
  - [HTML5 UTF-8中文乱码](http://www.cnblogs.com/csn0721/archive/2013/01/24/2875613.html)
  - [字符编码笔记：ASCII，Unicode和UTF-8](http://www.ruanyifeng.com/blog/2007/10/ascii_unicode_and_utf-8.html)
- [语言代码表 e.g. `<html lang="zh-CN">`](http://reference.sitepoint.com/html/lang-codes)
- [在谈语义化](http://ued.ctrip.com/blog/talk-about-semantic.html)
- [如何写出高效率的HTML](https://segmentfault.com/a/1190000002680822)
- [深入理解HTML5标签](https://segmentfault.com/a/1190000002695791)
- MDN: [HTML表单指南](https://developer.mozilla.org/zh-CN/docs/Web/Guide/HTML/Forms)
  - SMASHING MAGZINE: [Good articles about froms UX](https://www.smashingmagazine.com/tag/forms/)
  - [New Approaches to Designing Log-In Forms](https://www.smashingmagazine.com/2011/08/new-approaches-to-designing-login-forms/)
  - [An Extensive Guide To Web Form Usability](https://www.smashingmagazine.com/2011/11/extensive-guide-web-form-usability/)

### 1.3 CSS基础知识

- [CSS选择器](https://developer.mozilla.org/zh-CN/docs/Web/CSS/Reference#选择器)
  - [CSS伪类 Pseudo-classes](http://www.w3school.com.cn/css/css_pseudo_classes.asp)
  - [如何和何时使用CSS的`!important`](http://www.w3cplus.com/css/the-important-css-declaration-how-and-when-to-use-it.html)
- [你应该知道的一些事——CSS权重](http://www.w3cplus.com/css/css-specificity-things-you-should-know.html)
- Web字体
  - [中文字体网页开发指南](http://www.ruanyifeng.com/blog/2014/07/chinese_fonts.html)
  - [Web中文字体应用指南](https://ruby-china.org/topics/14005)
  - [CSS字体系列： `font-family`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/font-family)
  - [Serif和Sans-serif字体的区别](http://kb.cnblogs.com/page/192018/)
  - [网页字体设置你了解吗？](http://ued.ctrip.com/blog/web-page-font-settings-did-you-know.html)
  - [CSS3 @font-face](http://www.w3cplus.com/content/css3-font-face)
  - [CSS-TRICKS: Using @font-face](https://css-tricks.com/snippets/css/using-font-face/)
  - [CSS中使用`em`设置字体大小](http://www.w3cplus.com/css/px-to-em)
- Web颜色
  - [Web安全色](http://www.bootcss.com/p/websafecolors/)
  - [Web安全色：WebSafeColors.info](http://websafecolors.info/)
  - [Trendy Web Color Palettes and Material Design Color Schemes & Tools](http://www.awwwards.com/trendy-web-color-palettes-and-material-design-color-schemes-tools.html)
  - [An Introduction to Color Theory for Web Designers](http://webdesign.tutsplus.com/articles/an-introduction-to-color-theory-for-web-designers--webdesign-1437)
- CSS盒模型
  - [CSS盒模型概述](http://www.w3school.com.cn/css/css_boxmodel.asp)
  - [CSS盒模型](https://developer.mozilla.org/zh-CN/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
  - [学习CSS布局](http://zh.learnlayout.com/)
- [CSS3媒体查询 `@media`](https://developer.mozilla.org/zh-CN/docs/Web/Guide/CSS/Media_queries)
  - Google Developer: [Use CSS media queries for responsiveness](https://developers.google.com/web/fundamentals/design-and-ui/responsive/fundamentals/use-media-queries?hl=en) | [中文版](https://developers.google.com/web/fundamentals/design-and-ui/responsive/fundamentals/use-media-queries?hl=zh-cn)
- CSS定位、流、布局
  - [CSS定位 Positioning](http://www.w3school.com.cn/css/css_positioning.asp)
  - CSS-TRICKS: [All About Floats](https://css-tricks.com/all-about-floats/)
  - [CSS 定位与文档流](http://www.ituring.com.cn/article/198258)
  - 知乎：[在CSS中，用`float`和`position`的区别是什么？](https://www.zhihu.com/question/19588854)
  - [CSS定位系列解读博文](http://www.zhangxinxu.com/wordpress/?s=CSS+%E7%9B%B8%E5%AF%B9%2F%E7%BB%9D%E5%AF%B9%28relative%2Fabsolute%29%E5%AE%9A%E4%BD%8D%E7%B3%BB%E5%88%97)
  - [CSS: display](https://css-tricks.com/almanac/properties/d/display/)
  - [Kicking Ass with `diplay:table`](http://www.mattboldt.com/kicking-ass-with-display-table/)
  - [The Anti-hero of CSS Layout `display: table`](http://colintoh.com/blog/display-table-anti-hero)
- [CSS: list-style](https://css-tricks.com/almanac/properties/l/list-style/)
  
### 1.4 HTTP基础知识

- [HTTP协议简介](http://www.liaoxuefeng.com/wiki/001374738125095c955c1e6d8bb493182103fac9270762a000/001386832653051fd44e44e4f9e4ed08f3e5a5ab550358d000)
- 拓展阅读：[HTTP权威指南](http://book.douban.com/subject/10746113/)
- [HTTP方法：GET对比POST](http://www.w3school.com.cn/tags/html_ref_httpmethods.asp)

## Task 1 HTML\CSS\Git Basic

### Reading:
1. 知乎：[Web开发基础指南](http://www.zhihu.com/question/22689579)
3. 入门图书：Head First HTML&CSS, 2nd
4. [Learn to Code HTML&CSS](http://learn.shayhowe.com/html-css/)
4. [HTML/CSS Performance & Organization](http://learn.shayhowe.com/advanced-html-css/performance-organization/)

### Git

1. [Git - the simple guide](http://rogerdudler.github.io/git-guide/index.zh.html)
2. [图解Git](http://marklodato.github.io/visual-git-guide/index-zh-cn.html)
3. [Git from inside out](https://codewords.recurse.com/issues/two/git-from-the-inside-out)
2. [猴子都能懂的GIT入门](http://backlogtool.com/git-guide/cn/intro/intro1_1.html)
2. [Git Magic](http://www-cs-students.stanford.edu/~blynn/gitmagic/intl/zh_cn/)
3. [First Aid Git](http://ricardofilipe.com/projects/firstaidgit/#/): A searchable collection of the most frequently asked Git Questions
4. [Github Help](https://help.github.com/)
5. [搬进Github](http://gitbeijing.com/)
6. [Github Pull Request Tutorial](https://www.thinkful.com/learn/github-pull-request-tutorial)
5. [25个Git进阶技巧](http://linux.cn/article-5418-weibo.html)

### HTML:

1. [HTML入门：教你做一个简单的网站](https://www.thinkful.com/learn/html-tutorial-for-beginners)
1. MDN: [HTML入门](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Introduction)
2. [知乎：如何理解Web语义化](http://www.zhihu.com/question/20455165)
3. [Learn to Code HTML & CSS](http://learn.shayhowe.com/html-css/)
4. [20 HTML Elements for Better Text Semantics](http://www.sitepoint.com/20-html-elements-better-text-semantics/)
5. [10 Typical HTML Interview Exercises](http://www.sitepoint.com/10-typical-html-interview-exercises/)

### CSS & Layout:

1. CSS入门：https://developer.mozilla.org/zh-CN/docs/Web/Guide/CSS/Getting_started
2. 学习CSS布局：http://zh.learnlayout.com/no-layout.html
3. [CSS常见布局问题整理](http://www.cnblogs.com/0603ljx/p/4440449.html)
4. [60个有用的CSS代码片断](http://segmentfault.com/a/1190000002773955)
3. 淘宝UED：双飞翼布局 http://www.imooc.com/wenda/detail/254035
4. [stackoverflow: 3 column layout](http://stackoverflow.com/questions/20566660/3-column-layout-html-css)
5. [stackoverflow: Two column div layout with fluid left and fixed right column](http://stackoverflow.com/questions/5645986/two-column-div-layout-with-fluid-left-and-fixed-right-column)
5. [CSS3中的网格](http://yanhaijing.com/css/2014/04/01/grids-in-css3/)
5. CSS Flexible Box: [CSS3中弹性盒布局的最新版](http://www.cnblogs.com/0603ljx/p/4440449.html)
6. Tool: [How to Center in CSS](http://howtocenterincss.com/)
7. [HTML5+CSS3的响应式网页设计：自动适应屏幕宽度](http://yusi123.com/2539.html#0-tsina-1-79947-397232819ff9a47a7b7e80a40613cfe1)
8. [Responsive Web Design](http://learn.shayhowe.com/advanced-html-css/responsive-web-design/)
8. [An Introduction to Mobile-First Media Queries](http://www.sitepoint.com/introduction-mobile-first-media-queries)
9. [Responsive Design Best Practices for Big Project](https://medium.com/@elad/responsive-design-best-practices-for-big-projects-5a72e3ecdcd2)
10. [The 30 CSS Selectors you Must Memorize](http://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048)


## Task 2 JavaScript Basic

### Reading:

1. 推荐阅读：Head First HTML5 Programming
2. 推荐阅读：JavaScript高级程序设计，第3版
3. [Dive Into HTML5](http://diveintohtml5.info/)
4. [MDN: JavaScript Wiki](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
5. [Learn to Code Advanced HTML & CSS](http://learn.shayhowe.com/advanced-html-css/)

### HTML5

1. Tutorial: [Native HTML5 Drag and Drop API](http://www.html5rocks.com/en/tutorials/dnd/basics/)

### JavaScript

1. MDN: [JavaScript入门](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)
2. [JavaScript性能优化：加载和执行](http://www.ibm.com/developerworks/cn/web/1308_caiys_jsload/index.html)
5. MDN: [JavaScript正则表达式](https://developer.mozilla.org/en/docs/Web/JavaScript/Guide/Regular_Expressions)
6. MDN: [query selector](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector)
9. [MDN: Cookie](https://developer.mozilla.org/en-US/docs/Web/API/Document/cookie)
10. [w3school: Ajax基础教程](http://www.w3school.com.cn/ajax/index.asp)
11. Blog: [使用原生JavaScript封装Ajax](http://www.cnblogs.com/Webcom/p/3415295.html)
10. [Comet: 基于HTTP长连接的“服务器push”技术](http://www.ibm.com/developerworks/cn/web/wa-lo-comet/)
11. jsfiddle: [a simple countdown timer](http://jsfiddle.net/mrwilk/qVuHW/)
12. [Simple Ajax Auto-Complete Example](http://www.wilycode.com/simple-ajax-auto-complete-example/)
13. Tutorial: [使用原生JavaScript从0开始开发一个轮播图](http://g-liu.com/blog/2013/08/tutorial-basic-carouselslideshow-with-javascript/)

### Node.js

1. scotch.io: [Build a RESTful API Using Node and Express 4](https://scotch.io/tutorials/build-a-restful-api-using-node-and-express-4)
2. [Express跨域问题解决方案](http://blog.csdn.net/marujunyy/article/details/8852017)
3. 朴灵：[Node编码规范](http://www.ituring.com.cn/article/197990)


### Questions

3. 为什么JavaScript中0.1+0.2不等于0.3？[参看浮点数计算的基本问题](http://floating-point-gui.de/basic/)。
3. stackoverflow: [most efficient way to clone an object](http://stackoverflow.com/questions/122102/what-is-the-most-efficient-way-to-clone-an-object)
4. stackoverflow: [remove duplicate items from an array](http://stackoverflow.com/questions/9229645/remove-duplicates-from-javascript-array)
5. stackoverflow: [浏览器类型判断](http://stackoverflow.com/questions/9847580/how-to-detect-safari-chrome-ie-firefox-and-opera-browser)
6. stackoverflow: [creating the checkbox daynamically using javascript](http://stackoverflow.com/questions/866239/creating-the-checkbox-dynamically-using-javascript)
11. stackoverflow: [How to iterate JSON array in JavaScript](http://stackoverflow.com/questions/15496508/how-to-iterate-json-array-in-javascript)

## Task 3 JavaScript Advanced & Basic Web App Development

### Reading

1. JavaScript高级程序设计，第3版
2. [JavaScript: The Good Parts](http://proquest.safaribooksonline.com/book/programming/javascript/9780596517748)
3. [JavaScript: The Definitive Guide](http://proquest.safaribooksonline.com/book/programming/javascript/9780596517748)
4. [Learning Advanced JavaScript](http://ejohn.org/apps/learn/)
2. [Elogquent JavaScript](http://eloquentjavascript.net/)
3. [JavaScript Garden](http://bonsaiden.github.io/JavaScript-Garden/zh/)
3. 数据结构与算法JavaScript描述
4. 编写可维护的JavaScript
5. Effective JavaScript
6. [重新介绍JavaScript](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/A_re-introduction_to_JavaScript)

### Debug

1. [Debugging JavaScript](https://developer.chrome.com/devtools/docs/javascript-debugging)
2. [Debugging Asynchronous JavaScript with Chrome DevTools](http://www.html5rocks.com/en/tutorials/developertools/async-call-stack/)
3. [Breakpoint Actions in JavaScript](http://www.randomthink.net/blog/2012/11/breakpoint-actions-in-javascript/)
4. [Evaluating Network Performance](https://developer.chrome.com/devtools/docs/network)
2. [Enhance your javascript debugging with Cross-Browser Source Maps](http://www.sitepoint.com/enhance-your-javascript-debugging-with-cross-browser-source-maps/)

### JavaScript

1. [5个经典的JavaScript面试题](http://wwsun.me/posts/javascript-interview.html)
2. [鸟哥：理解JavaScript的作用域](http://www.laruence.com/2009/05/28/863.html)
3. [JavaScript 开发进阶：理解 JavaScript 作用域和作用域链](http://www.cnblogs.com/lhb25/archive/2011/09/06/javascript-scope-chain.html)
4. [Understanding JavaScript Prototypes](https://javascriptweblog.wordpress.com/2010/06/07/understanding-javascript-prototypes/)
5. [A Plain Guide to JavaScript Prototypes](http://sporto.github.io/blog/2013/02/22/a-plain-english-guide-to-javascript-prototypes/)
6. [详解JavaScript的函数闭包](http://wwsun.me/posts/javascript-closure.html)
7. [Revealing the Inner Workings of JavaScript's 'this' keyword](http://www.sitepoint.com/inner-workings-javascripts-this-keyword)
8. [JavaScript like a Boss: Understanding Fluent APIs](w.sitepoint.com/javascript-like-boss-understanding-fluent-apis)
9. stackoverflow: [Storing Objects in HTML5 localStorage](http://stackoverflow.com/questions/2010892/storing-objects-in-html5-localstorage)
10. stackoverflow: [Copying array by value in JavaScript](http://stackoverflow.com/questions/7486085/copying-array-by-value-in-javascript)


### JavaScript OOP

1. [Javascript 面向对象编程基础入门](http://www.ruanyifeng.com/blog/2010/05/object-oriented_javascript_encapsulation.html)
2. 推荐阅读：JavaScript高级程序设计，第6章，面向对象程序设计
2. [JavaScript继承详解](http://www.cnblogs.com/sanshi/archive/2009/07/08/1519036.html)
3. [JavaScript继承方式详解](http://segmentfault.com/a/1190000002440502)
4. [JavaScript探秘：构造函数 Constructor](http://www.nowamagic.net/librarys/veda/detail/1642)
5. [this关键字详解](http://www.cnblogs.com/justany/archive/2012/11/01/the_keyword_this_in_javascript.html)
6. [深入浅出JavaScript中的this关键字](http://www.ibm.com/developerworks/cn/web/1207_wangqf_jsthis/index.html)

### Design Patterns

1. [常用的JavaScript设计模式](http://blog.jobbole.com/29454/)
2. [JavaScript设计模式深入分析](http://developer.51cto.com/art/201109/288650.htm)
3. 图书：[Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/)
4. [上面这本书的中文版](http://www.oschina.net/translate/learning-javascript-design-patterns)

### HTML & CSS

1. [Using Links to Create Navigation Menus](http://webdesign.about.com/od/css/a/aa082304.htm)
2. Stackoverflow: [CSS3 Viewport-Percentage Length](http://stackoverflow.com/questions/1575141/make-div-100-height-of-browser-window)
3. Tutorial: [Horizontal lists](http://css.maxdesign.com.au/listutorial/horizontal_master.htm)
4. Tutorial: [Creating a modal window with HTML5 & CSS3](http://www.webdesignerdepot.com/2012/10/creating-a-modal-window-with-html5-and-css3/)

### Documentation

1. [MDN JavaScript全部页面索引](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/A_re-introduction_to_JavaScript)
2. [MDN JavaScript全部方法索引](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Methods_Index)
3. [MDN JavaScript全部属性索引](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Properties_Index)

## Task 4 Mobile and Engineering

### Mobile Development

1. Book: Head First Mobile Web
1. [Mobile First Design: Why It’s Great and Why It Sucks](http://designshack.net/articles/css/mobilefirst/)
2. [Mobile Development Get Started](http://junmer.github.io/mobile-dev-get-started)
2. [移动开发资源与技巧汇总](https://github.com/jtyjty99999/mobileTech)
3. [The Mobile Web Handbook](http://quirksmode.org/mobilewebhandbook/)
4. [5 Quick Ways to Make Your Site More Mobile Friendly](http://designshack.net/articles/webstandards/5-quick-ways-to-make-your-site-more-mobile-friendly/)
4. [MobileWeb 适配总结](http://www.w3ctech.com/topic/979)
5. [移动前端不得不了解的html5 head 头标签](http://www.css88.com/archives/5480)
6. [浅谈移动前端的最佳实践](http://www.cnblogs.com/yexiaochai/p/4219523.html)
7. [touch系事件](http://www.html-js.com/article/All-right-thinking-touch-events)
8. [移动端真机调试终极利器-BrowserSync](http://www.codingserf.com/index.php/2015/03/browsersync/)
9. [Webstorm: Getting started with hybrid mobile app development](https://confluence.jetbrains.com/display/WI/Getting+started+with+hybrid+mobile+app+development)
10. [Browser-Sync：响应式Web开发调试利器](http://www.imooc.com/wenda/detail/265741)

### CSS pre-process and post-process

1. [再谈 CSS 预处理器](http://efe.baidu.com/blog/revisiting-css-preprocessors/)
2. [CSS 预处理器与 CSS 后处理器](http://zhaolei.info/2014/01/04/css-preprocessor-and-postprocessor/)
3. [SASS Basics](http://sass-lang.com/guide)
4. [The Sass way](http://thesassway.com/)

### Modular

1. [阮一峰：Javascript模块化编程（一）：模块的写法](http://www.ruanyifeng.com/blog/2012/10/javascript_module.html)
2. [详解JavaScript模块化开发](http://segmentfault.com/a/1190000000733959)
2. [为什么需要AMD?](http://requirejs.org/docs/whyamd.html)
2. [服务器端模块规范：RequireJS](http://requirejs.org/)
3. [CMD实现:Sea.js](http://seajs.org/docs/#intro)
3. [SeaJS与RequireJS最大的区别](http://www.douban.com/note/283566440/)
4. [知乎：LABjs、RequireJS、SeaJS 哪个最好用？为什么？](http://www.zhihu.com/question/20342350)
5. [Youtube: RequireJS made ridiculously easy, in just 10ish minutes](https://www.youtube.com/watch?v=eRqsZqLyYaU)
5. [Understanding RequireJS for Effective JavaScript Module Loading](http://www.sitepoint.com/understanding-requirejs-for-effective-javascript-module-loading/)
6. [Using RequireJS in AngularJS Applications](http://www.sitepoint.com/using-requirejs-angularjs-applications/)
5. [Organizing your application using Modules (require.js)](http://backbonetutorials.com/organizing-backbone-using-modules/)
5. [百度EFE：玩转AMD - 写在前面](http://efe.baidu.com/blog/dissecting-amd-preface/)
6. [百度EFE：玩转AMD - 设计思路](http://efe.baidu.com/blog/dissecting-amd-what/)
7. [百度EFE：玩转AMD - 应用实践](http://efe.baidu.com/blog/dissecting-amd-how/)
8. [百度EFE：玩转AMD - Loader](http://efe.baidu.com/blog/dissecting-amd-loader/)
9. [百度ESL (Enterprise Standard Loader)](https://github.com/ecomfe/esl)
10. [浏览器加载CommonJS模块的原理与实现](http://www.ruanyifeng.com/blog/2015/05/commonjs-in-browser.html)

### Front-end Engineering

1. [前端工程与模块化框架](http://div.io/topic/439)
2. [手机百度前端工程化之路](http://mweb.baidu.com/p/baidusearch-front-end-road.html)
3. [视频：FIS2.0全新的百度前端解决方案（范云龙）](http://www.infoq.com/cn/presentations/baidu-new-front-end-solutions-fis)
4. [InfoQ: 对话百度前端工程师张云龙：F.I.S与前端工业化](http://www.infoq.com/cn/articles/yunlong-on-fis)
5. [Grunt教程——初涉Grunt](http://www.w3cplus.com/tools/grunt-tutorial-start-grunt.html)
6. [Gulp入门指南](http://www.open-open.com/lib/view/open1417068223049.html)

### Website Performance

5. [大型网站的灵魂——性能](http://www.cnblogs.com/leefreeman/p/3998757.html)
2. [Google: Web性能最佳实践](https://developers.google.com/speed/docs/insights/rules)
3. [毫秒必争，前端网页性能最佳实践](http://www.cnblogs.com/developersupport/p/webpage-performance-best-practices.html)
3. Yahoo: [Best Practices for Speeding Up Your Web Site](https://developer.yahoo.com/performance/rules.html)
1. [14 Rules for Faster-Loading Web Site](http://stevesouders.com/hpws/rules.php)
2. Video: [Practical Performance Tips to Make Your HTML/JavaScript Faster](http://channel9.msdn.com/Series/Practical-Performance-Tips-to-Make-Your-HTMLJavaScript-Faster)
3. [前端性能优化最佳实践](http://caibaojian.com/webfront-practice.html)
4. [CSS Sprite原理、优缺点及使用](http://www.cnblogs.com/mofish/archive/2010/10/12/1849062.html)
5. [伯乐在线：编写高效的 CSS 选择器](http://web.jobbole.com/35339/)

### Performance Debug Tools

1. [Chrome developer tools](https://developer.chrome.com/devtools)
2. [Web Page Test](http://www.webpagetest.org/)
3. [Windows Performance Toolkit Overview](https://msdn.microsoft.com/enus/library/windows/hardware/hh162981.aspx)

## Advanced Topic

### Helpers

1. 文件精简工具：[UglifyJS](https://github.com/mishoo/UglifyJS2)
2. 构建工具：[Grunt: The JavaScript Task Runner](http://gruntjs.com/)
3. 构建工具：[Gulp: the streaming build system](https://github.com/gulpjs/gulp)
4. 文档生成：[jsdoc: an api documentation generator for JavaScript](https://github.com/jsdoc3/jsdoc)
5. 代码检查：[JSHint](https://github.com/jshint/jshint)
6. 测试框架：[Jasmine](http://jasmine.github.io/)
6. Test Runner：[Karma](http://karma-runner.github.io/0.12/index.html)
7. [Bower：Web前端包管理工具](http://bower.io/)
8. [Yeoman: 帮你快速启动新项目](http://yeoman.io/)
9. [Travis CI：持续集成工具](https://travis-ci.org/)

### JavaScript MVC Frameworks

1. [Angular.js](https://angularjs.org/) & [Angular2](https://angular.io/)
2. [React.js](https://facebook.github.io/react/) & [React Native](https://facebook.github.io/react-native/)
3. Tutorial: [AngularJS in 30 minutes](http://www.revillweb.com/tutorials/angularjs-in-30-minutes-angularjs-tutorial/)
4. [AngularJS风格指南](https://github.com/johnpapa/angular-styleguide/blob/master/i18n/zh-CN.md)

### CSS Frameworks 

1. [Bootstrap 3](http://v3.bootcss.com/css/)
2. [Semantic UI](http://semantic-ui.com/)
3. [Materialize：Material design](http://materializecss.com/)
2. [Top 5 Material Design Frameworks to Use in 2015](http://www.sitepoint.com/top-5-material-design-frameworks-use-2015)

## Contact me

1. My profile: http://wwsun.me/about.html
2. My Github: https://github.com/wwsun
3. My Weibo: http://weibo.com/234170023