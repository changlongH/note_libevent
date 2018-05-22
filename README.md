# Libevent 


## what  

- [libevent 官网介绍](http://www.wangafu.net/~nickm/libevent-2.1/doxygen/html/)

## how

- [libevent 学习教程](http://www.wangafu.net/~nickm/libevent-book/)

## why

* 几种网络I/O模式


* 网络协议栈（SKB）


* select/epoll 


* reactor模型


* libevent 


* bufferevent


* libevent 定时器







### tips 

 ./configure --enable-debug-mode --enable-static --enable-thread-support --prefix=~/libevent

gcc -g -o a.out -I ~/libevent/include/ -L ~/libevent/lib/ hello-world.c -levent
