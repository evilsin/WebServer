# webser
基于Linux的轻量级高并发Web服务器

项目描述：使用C++在Linux环境下搭建轻量级、高性能、高并发的Web服务器，能够支持相对数量的客户端并发访问并及时响应，在该项目中服务器支持客户端访问服务器上的图片等内容

开发环境：Linux，Visual Studio Code，C++，gcc，gdb

项目技术点：线程池+非阻塞socket+epoll+事件处理的并发模型，主从状态机高效解析HTTP请求
