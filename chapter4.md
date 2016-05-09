# JS打包插件

* js init loader， 解决每个不同html页面引入不同js胶水代码
* js module loader， 解决每个不同html页面引入不同js模块代码
* js compiler， 解决每个不同html页面加载过多js文件的问题

JS打包插件使用的技术是

* AOP
* 利用闭包生成函数
* 文件管道流

这里讲一个小故事，文件管道流别忘了自我回路。未来属于你。