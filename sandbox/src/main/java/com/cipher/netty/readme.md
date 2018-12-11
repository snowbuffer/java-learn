## Netty 入门与实战：仿写微信 IM 即时通讯系统

### A. Netty 与传统网络编程的区别

    客户端每隔两秒发送一个带有时间戳的 "hello world" 给服务端，服务端收到之后打印。

- 传统IO编程
        
- JDK NIO 实现

- Netty 实现

### B. 服务端和客户端启动流程

### C. 客户端和服务端双向通信

    客户端连接成功之后，向服务端写一段数据 ，服务端收到数据之后打印，并向客户端回一段数据
   
### D. 客户端登录

    实现客户端登录到服务端的过程
    
### E. 客户端与服务端收发消息

    在控制台输入一条消息之后按回车，校验完客户端的登录状态之后，把消息发送到服务端，服务端收到消息之后打印并且向客户端发送一条消息，客户端收到之后打印