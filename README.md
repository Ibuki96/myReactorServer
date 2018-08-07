# myReactor: a reactor implementation
# myServer: a http server implementation based on myReactor

## 测试环境
* OS：Ubuntu 16.10
* 内存：8G
* CPU：I5-6300HQ

## 测试方法
* [reference:](https://github.com/linyacool/WebServer/blob/master/%E6%B5%8B%E8%AF%95%E5%8F%8A%E6%94%B9%E8%BF%9B.md)


## 测试结果及分析
测试截图放在最后  

| 服务器 | 短连接QPS | 长连接QPS | 
| - | :-: | -: | 
| myServer | 48395| 153570 | 
| Muduo | 47533 | 118139 | 

* analysis 1 
* analysis 2
* analysis 3


## 测试结果截图
* myServer短连接测试  
![shortMyServer](https://github.com/linyacool/WebServer/blob/master/resources/myServer.png)
* muduo短连接测试  
![shortMuduo](https://github.com/linyacool/WebServer/blob/master/resources/muduo.png)
* myServer长连接测试  
![keepMyServer](https://github.com/linyacool/WebServer/blob/master/resources/myServerK.png)
* muduo长连接测试  
![keepMuduo](https://github.com/linyacool/WebServer/blob/master/resources/muduoK.png)
* myServer空闲负载  
* myServer短连接CPU负载  
* myServer长连接CPU负载  

