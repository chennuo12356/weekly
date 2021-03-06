Node.js 资源汇总
========
	
	begin at 2014.06 持续更新
	
## Framework

**NodeBB**  
https://nodebb.org/  
A better faster forum platform for the modern web.  
The next generation forum software that's free and easy to use. 

**MEAN**  
http://mean.io/  
The Friendly & Fun Javascript Fullstack for your next web application
MEAN is an opinionated fullstack javascript framework - which simplifies and accelerates web application development.

## 进程&服务管理

forever  nodemon  pm2  supervisor

forever 的接口不是很好，功能也没有 pm2 强大。启动同名文件时需要 --uid 参数，每次启动还得加 -a ，挺烦的。更多请参考：

- [Goodbye node-forever, hello PM2](http://devo.ps/blog/goodbye-node-forever-hello-pm2/)
      
推荐： nodemon  pm2 ，但 pm2 的 cluster_mode 不太稳定，建议优先选 fork_mode


## 异步编程

Async.js  
Q  
FRP(Functional Reactive Programming)  

推荐从 Async 入手，简单强大，比 Q 容易上手。

python 中有 asyncio 

## Server

**[Harp](http://harpjs.com/)** : The static web server with built-in preprocessing. Harp serves Jade, Markdown, EJS, CoffeeScript, Sass, LESS and Stylus as HTML, CSS & JavaScript—no configuration necessary.

## 技术文章

收录一些经典文章：

- [Farewell Node.js](https://medium.com/code-adventures/farewell-node-js-4ba9e7f3e52b)
- [Error Handling in Node.js](https://www.joyent.com/developers/node/design/errors)
- [为什么 Node.js 这么火，而同样异步模式 Python 框架 Twisted 却十几年一直不温不火？](http://www.zhihu.com/question/23854296/answer/27877645)
- [如何看待 TJ 宣布退出 Node.js 开发，转向 Go](http://www.zhihu.com/question/24373004)
- [如何评价淘宝 UED 的 Midway Framework 前后端分离](http://www.zhihu.com/question/23512853)

