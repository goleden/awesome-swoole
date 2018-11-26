# Awesome Swoole [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

本项目主要是和Swoole相关的资源列表，同时也包含PHP扩展开发, PHP框架和网络编程相关的的资源。

Swoole是使用C语言编写的PHP扩展，实现了异步、并行、高性能的网络通信，网上有很多基于Swoole开发的项目。

- [项目](#项目)
  - [Swoole项目](#Swoole项目)
  - [php扩展项目](#php扩展项目)
- [资源](#资源)
  - [Swoole](#Swoole)
  - [php扩展](#php扩展)
  - [php内核](#php内核)
  - [网络编程](#网络编程)
- [其他列表](#其他列表)
- [贡献](#贡献)

- - -

## 项目

### Swoole框架

- [mixstart/mixphp](https://github.com/mixstart/mixphp) - 基于 Swoole 的FPM、常驻内存、协程三模 PHP 高性能框架
- [Tars-PHP](https://github.com/Tencent/Tars/tree/phptars) -(@Tencent) PHP版的TARS微服务部署运维解决方案
- [mysql_proxy](https://github.com/swoole/mysql-proxy) - (@GXhua) mysql 中间件
- [Swoft](https://github.com/swoft-cloud/swoft) - (@swoft-cloud) 基于Swoole原生协程，新时代PHP高性能协程框架
- [easyswoole](https://github.com/kiss291323003/easyswoole) - (@kiss291323003) easySwoole 专为API而生，是一款常驻内存化的PHP开发框架
- [SwooleDistributed](https://github.com/tmtbe/SwooleDistributed) - (@tmtbe) swoole 分布式全栈框架
- [CatSystem](https://github.com/CatsSystem) - (@CatsSystem) 基于 Swoole 的高性能开发套件
- [Blink](https://github.com/bixuehujin/blink) - (@bixuehujin) Web 微型高性能框架
- [multiprocess](https://github.com/kcloze/multiprocess) - (@kcloze) PHP multiprocess manager for cli, 可轻松让普通PHP脚本变守护进程和多进程执行
- [keeper](https://github.com/chongyi/keeper) - (@chongyi) 基于 Swoole 的后台多进程程序脚手架，提供了基本的进程控制功能
- [statistics](https://github.com/smalleyes/statistics) - (@smalleyes) 一个运用 php 与 swoole 实现的统计监控系统
- [Sworm](https://github.com/heikezy/Sworm) - (@heikezy) 基于 Swoole 的异步 MySQL 数据库 ORM 框架
- [FastD](https://github.com/JanHuang/fastd) - (@JanHuang) 基于Swoole的微型API框架(A high performance PHP API framework. [https://fastdlabs.com](https://fastdlabs.com))
- [zhttp](https://github.com/keaixiaou/zhttp) - (@keaixiaou) 基于 Swoole 的异步轻量级web框架
- [swooletw/laravel-swoole](https://github.com/swooletw/laravel-swoole) - 基于swoole的高性能http服务器。加快Laravel或Lumn应用程序。
- [LaravelFly](https://github.com/scil/LaravelFly) - (@scil) 用swoole http server运行Laravel的项目
- [LaravelS](https://github.com/hhxsv5/laravel-s) - (@hhxsv5) 通过Swoole来加速 Laravel/Lumen，其中的S代表Swoole，速度，高性能
- [IMI](https://github.com/Yurunsoft/IMI) - (@Yurunsoft) 基于 Swoole 开发的协程 PHP 开发框架


### Swoole相关项目


### php扩展项目

- [PHP_X](https://github.com/swoole/PHP-X) - (@matyhtf) C++ wrapper for Zend API
- [donkeyid](https://github.com/osgochina/donkeyid) - (@osgochina) 64位自增id生成器
- [Pimple](https://github.com/silexphp/Pimple) - (@silexphp) 依赖注入容器的php扩展实现版

## 资源

### Swoole

- [Swoole源码](https://github.com/swoole/swoole-src)
- [Swoole官方文档](https://wiki.swoole.com/)
- [Swoole文档](https://linkeddestiny.gitbooks.io/easy-swoole/content/)
- [Swoole问答](http://group.swoole.com/)
- [Swoole更新记录](https://wiki.swoole.com/wiki/page/p-project/change_log.html)

### php扩展

- (书)[PHP扩展开发与内核应用](http://www.cunmou.com/phpbook/index.md)
- (文档)[PHP核心：骇客指南](http://php.net/manual/zh/internals2.php) - PHP官方文档
- (slide)[PHP Extensions - What and Why](https://derickrethans.nl/talks/phpexts-zendcon11.pdf) - Derick Rethans(xdebug的作者)在ZendCon的分享

### php内核

- (书)[PHP7内核剖析](https://github.com/pangudashu/php7-internal) [豆瓣链接](https://book.douban.com/subject/27197032/) 实体书已出版
- [深入理解PHP内核](http://www.php-internals.com/)
- [PHP-Internals-Book](https://github.com/phpinternalsbook/PHP-Internals-Book)
- [nikic的博客](http://nikic.github.io/) - PHP内核开发者，PHP-Parser作者
- [鸟哥的博客](http://www.laruence.com/)

### 网络编程

- (项目)[libevent](https://github.com/libevent/libevent)
- (项目)[libev](https://github.com/enki/libev)
- (项目)[libeio](https://github.com/scunningham/libeio)
- (项目)[libuv](https://github.com/libuv/libuv)
- (书)[TCP/IP网络编程](https://book.douban.com/subject/25911735/) - 通俗易懂，适合入门
- (书)[UNIX网络编程 卷1：套接字联网API](https://book.douban.com/subject/4859464/)
- (书)[Linux高性能服务器编程](https://book.douban.com/subject/24722611/)
- (书)[UNIX网络编程 卷2：进程间通信](https://book.douban.com/subject/26434599/)

## 其他列表

- [PHP 资源大全中文版](https://github.com/jobbole/awesome-php-cn)

## 贡献本项目

如果你有以上未收录的关于Swoole或者php扩展的资源，欢迎提交PR
