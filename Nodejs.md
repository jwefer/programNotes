## NodeJs

### 1. Node简介

- Node.js是一个能够在**服务器端**运行JavaScript的开放源代码、跨平台JavaScript运行环境

- goole发开的v8引擎运行，使用**事件驱动**、**非阻塞**和**异步I/O模型**等技术来提高性能

- Node单线程，为解决web服务器的高并发性能问题，I/O进程会阻塞程序运行
- Node是对ES标准的一个实现，其中不包含DOM和BOM，Node也是一个js引擎
- 通过Node可以使js代码在服务器端执行

- Node中可以使用所有的内建对象`String Number Boolean Math Date RegExp Function Object Array`而DOM和BOM都不能使用，但可使用console和定时器

- Node可以在后台来编写服务器

  - 单线程服务器

  - 进程：一个一个的工作计划（工厂车间）

  - 线程：计算机最小的运行单位（工厂工人，线程是干活的）

- 传统的服务器都是多线程的：每进来一个请求，都创建一个线程去处理

- Node服务器是**单线程**的，但是咋以后台拥有一个I/O线程池（I/O指对磁盘的读写操作）

------

### 2. Node的用途

1. Web服务API，比如REST
2. 实时多人游戏
3. 后端的web服务，例如**跨域**、服务端请求
4. 基于web的应用
5. 多客户端的通信，如及时通信

------

