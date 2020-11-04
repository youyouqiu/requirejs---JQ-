# requirejs---JQ-
requirejs使用结构-基于原生或JQ编程

入口文件：index.html
require.js插件
用来给以前未使用框架开发的老程序做拆分优化
主js文件：main.js
拆分a.js => c, d, e.js
拆分b.js => f, g, h.js
从a, b.js中拆分变量，数据存储：data.js
从a, b.js中拆分公共函数：publicFun.js
