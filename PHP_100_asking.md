# PHP面试 100 问

## 第 1 问

session 和 cookie 的区别与联系？

- 数据存储：
  session 会话数据储存在服务端， cookie 数据存储在用户浏览器中。
- 标识传递：
  session_id 或者 cookie_name 都是通过 http 请求头的 cookie 字段传递。
- 数据保护性
  session 数据在服务端，具有很好的保护。 cookie 是透明的。
  
## 第 2 问

什么是单点登录，如何实现单点登录？

## 第 3 问

乐观锁和悲观锁的区别？

## 第 4 问

MySQL 性能优化有哪些手段？

## 第 5 问

如何防止 SQL 注入？

## 第 6 问

XSS 攻击如何实现，如何防止？

## 第 7 问

CSRF 攻击如何实现，如何防止？

## 第 8 问

PSR 是什么？

## 第 9 问

Git 常用的命令有哪些？

## 第 10 问

对于加班，你怎么看？

## 第 11 问

如何排查线上的 API 接口性能问题？

## 第 12 问

对于自己搞不定的项目任务，你会怎么处理？

## 第 13 问

PHP 处理请求的生命周期，LNMP （PHP-FPM模式下）四者是如何协作的？

## 第 14 问

提升 PHP 应用代码性能，有哪些方法？

## 第 15 问

PHP7 有哪些新的语法糖，或其它变动？

## 第 16 问

swoole 是什么？它比 PHP-FPM 性能高在哪里？

## 第 17 问

opcode 是什么？

## 第 18 问

如果可以，你希望未来的 PHP8 增加哪些新的特性？

## 第 19 问

你用过什么 web 开发框架，如何设计一个 web 开发框架？

## 第 20 问

CDN 是什么？

## 第 21 问

进程和线程的区别？

## 第 22 问

如何架构一套单秒并发 1000 次左右的秒杀抢购活动的后端服务？

## 第 23 问

微服务是什么？

## 第 24 问

如何分库分表？

## 第 25 问

MySQL 设计表有技巧？

## 第 26 问

socket 是什么？

## 第 27 问

什么是设计模式，你了解的设计模式有哪些？

## 第 28 问

什么是单一职责原则？

## 第 29 问

产品经理提出了你实现不了的需求，你该如何处理？

## 第 30 问

你们上线发布的流程是怎样的？什么是 DevOps？

## 第 31 问

线上出了偶现 BUG，你该如何排查？

## 第 32 问

MVC 是什么？

## 第 33 问

为什么 PHP 性能一般，还如此受欢迎？

## 第 34 问

谈谈你对 PHP 垃圾回收机制的了解。

## 第 35 问

PHP generator 如何使用？

## 第 36 问

PHP trait 的作用是？

## 第 37 问

什么是 DI (依赖注入)？

## 第 38 问

平时用过什么建模工具？

## 第 39 问

什么是 NoSQL 数据库，它跟关系型数据库的区别有哪些，你用过什么 NoSQL 数据库？

## 第 40 问

Redis 有哪些数据类型？Redis 如何实现消息队列？

## 第 41 问

你用过什么 linux 系统？常用的命令有哪些？

## 第 42 问

你的职业生涯规划是怎样的？

## 第 43 问

现在要设计一套 IM（即时通信）系统，请问你该如何进行技术选型？

## 第 44 问

websocket 是什么？

## 第 45 问

memcache CAS 原理。

## 第 46 问

作为内存缓存，redis 和 memcache 你该如何选择？

## 第 47 问

你在 linux 上开发过 PHP 原生扩展吗？开发的基本流程是？

## 第 48 问
composer 是什么，如何创建一个自己的 composer package？

## 第 49 问

composer 实现原理。

## 第 50 问

RPC 是什么？

## 第 51 问

Linux 定时任务如何实现？

## 第 52 问

做过 Android 系统推送消息吗，如果实现高吞吐、低时延？

## 第 53 问

做过微信支付吗，谈谈微信支付的开发流程。

## 第 54 问

如何保障 PHP 应用的高可用？

## 第 55 问

什么是内存泄漏，如何预防和发现以及解决？

## 第 56 问

32 位和 64 位的 PHP 版本有哪些区别，NTS 和 TS 版本的 PHP 有哪些区别？

## 第 57 问

SAPI 是什么，PHP 有哪些常用的 SAPI？

## 第 58 问

你认为高级 PHPer 应该具备哪些能力？现在的你是高级 PHPer 吗？

## 第 59 问

平时你使用的 PHP 工具链是？

## 第 60 问

CGI 和 FastCGI 的区别？

## 第 61 问

简单介绍一下 PHP-FPM 的工作模式？

## 第 62 问

PHP 如何创建一个子进程？

## 第 63 问

你了解哪些数据结构和算法？

## 第 64 问

谈谈你对 PHP 浮点数问题的了解，如何解决？

## 第 65 问

有自己的开源项目吗？GitHub 和 Stack Overflow 以及 Google 这些网站是否使用？

## 第 66 问

HTTP GET 和 POST 的区别？

## 第 67 问

请写出 1 年前的今天是几月几号的代码？

## 第 68 问

MySQL 数据表引擎有哪些？

## 第 69 问

MySQL 事务是什么？

## 第 70 问

PHP 的魔术方法和魔术常量有哪些，作用是？

## 第 71 问

谈谈你对 PHP 静态延迟绑定的了解？

## 第 72 问

异步和同步的编程的区别？

## 第 73 问

前端和后端如何实现完全分离？

## 第 74 问

ajax 是什么，使用过 jQuery 吗，使用过 vue 吗？
 
## 第 75 问

Docker 容器技术使用过吗，常用的命令有哪些？

## 第 76 问

服务器的 TIME_WAIT 连接数过多，如何解决？

## 第 77 问

TCP和UDP的区别，TCP的三次握手过程分别是？

## 第 78 问

查看进程，查看内存，查看磁盘，查看 CPU 等负载的命令有哪些？

## 第 79 问

获取一张远程图片 http://example.com/hello.jpg 有哪些方法？

## 第 80 问

谈谈你对 interface 的理解。

## 第 81 问

请用递归算法实现阶乘的计算？例如 1!= 1,2!=1*2,3!=1*2*3,以此类推

## 第 82 问

如何获取一段包含中文的文本中的子串，要求不能出现乱码？

## 第 83 问

请使用 PHP 代码实现 `order by` 的多字段分组排序功能。例如现从数据库中查询出了`$itemList = [["id"=>1,"name"=>"张三","age"=>45],["id"=>2,"name"=>"李四","age"=>32],["id"=>5,"name"=>"王二","age"=>19]]` 3 条记录，需要按照 `order by name asc, age desc,id asc`等功能

## 第 84 问

谈谈你对 UTF8 编码的了解。

## 第 85 问

使用过阿里云的云服务器吗，弹性云计算的含义是什么，通常你会如何选择云服务器，什么是可用区，什么是安全组？

## 第 86 问

谈谈你对大数据和机器学习的了解，贝叶斯理论是什么？

## 第 87 问

谈谈你对 DDOS 攻击的了解，如何实现 DDOS 攻击，如何防治？

## 第 88 问

谈谈你对 http 和 https 以及 http2 的了解。

## 第 89 问

什么是 BigPipe？

## 第 90 问

异步非阻塞在 PHP 中是如何实现的，谈谈你对 JavaScript 中的 async 和 await 的了解？

## 第 91 问

Linux 为什么偏好多进程，而不是多线程，PHP 如何实现多线程编程？

## 第 92 问

脚本进程管理工具有哪些，supervisor 和 pm2 有使用过吗？

## 第 93 问

谈谈你对 CSS 盒子模型， JavaScript 原型链的理解。

## 第 94 问

为了加快开发速度，有时候需要寻找满足需求的开源项目，你是如何选择一个合适的开源项目？

## 第 95 问

谈谈你对单元测试的了解，黑盒测试和白盒测试的概念，PHP如何实现单元测试。

## 第 96 问

什么是持续集成/持续交付，分布式的PHP应用如何实现？

## 第 97 问

Linux 下的 sed 和 awk 文本查找工具使用过吗？

## 第 98 问

如何排查 MySQL 性能过低的问题？

## 第 99 问

nginx 如何实现 PHP 应用的负载均衡？

## 第 100 问

nginx 的 proxy_pass 和 fastcgi_pass 是什么，如何保持长连接？


