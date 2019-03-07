# natural
## 基于ES6的WEB前端框架  
一直以来很想自己写一个简单的基于原生前端框架。  
这样的框架具有：学习成本低，可扩展性强，团队协作性强，耦合性低，当然还要保持性能。    
最主要的是归还前端一个干净的世界，保持HTML CSS JAVASCRIPT 原有的特性，让使用者不要学习一堆新概念。  

该项目建立有快有两年了，说了惭愧，一直没有动手行动。之前一直在游戏行业，到2016年7月才回归WEB前端，当时任务紧张，捡起一本《javascript 高级编程3》就开干。凭借多年编游戏框架的代码的经验，稀里哗啦的两周就搭了个SD框架，后来结合着vue1.0 ,也没有什么webpack打包，自己随手写了个nodejs打包文件，凑合着放到服务器上自动打包。当时十来个前端配合着用，居然还能让好几个项目在上线跑起来！

现在回过头来看，还是有很多不足的地方，虽然中间填了许多坑。最搞笑的是最近一面试官让我说一说整体架构的设计思想，我居然一脸懵逼的卡壳了。我想：设计思想什么鬼？当时就想着怎么好用，怎么好让新人快速上手开发，最多只需要简单培训一下，因为总共就1千多行代码；然后vue1.0文档线上自己看去；什么构建工具都不用去搭理，只用专注代码逻辑开发上（太多的事实证明运行效率大部分原因都是程序员业务逻辑上的问题，而不是所谓的框架，再牛逼的框架程序员都可以让他死给你看……）。

随着深入了解市面上的一些主流框架，中间尝试过多种写法，还组织过公司所有前端一起参与新框架sd2.0的开发。最终都不是特别让人满意，感觉有些思路始终被vue，react等牵着鼻子了，最后大家放弃了，既然思路一样就直接用上了vue2。

-  后来大部分项目升级到vue2 ，只留下一个收银项目还在用。地址：https://pos.shandian.net/

最近被失业一逼倒好了，认真的思考了技术上的事情来，重新整起来。先认真学习了一波：认识了什么是《css 禅意花园》；html语义化标签；SPA路由的概念与现有的实现手段；虚拟DOM的原理和优点；Layui（这家伙理念有点和我的接近，但又不是）；Javascript的运行机制；计时器，事件，携程，多线程，es6的模块化，文件加载机制，前端规范的演变等等。恩很好，静下来认真思考。

一个惊人的发现：到现在很少有人谈规范了，都交给了webpack，rullup等，现在面试官一般都问你会这个那个配置吗,感觉现在是配置工程师时代了，这势必会让人技术倒退不是吗？我不太想把框架整成这样，还是回归自然一点好，公共文件自己管理就好，要打包自己控制就好，框架与业务应该和构建功能分离开来，充其量就是一个工具。

这回的想法很棒!!开始行动！！
