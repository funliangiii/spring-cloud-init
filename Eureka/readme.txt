1.client_server

client_server是搭建注册中心以及将一个客户端注册到注册中心的例子。
运行例子步骤：
1.导入到IEAD
2.运行eureka_server模块main方法，启动注册中心
3.运行eureka_client模块main方法，启动客户端
4.浏览器输入：http://localhost:9001/查看客户端注册前后的变化

2.eureka-server-high-availability
eureka-server-high-availability是搭建注册中心高可用的例子
1.导入到IEAD
2.运行eureka_server_1模块中的main方法
3.运行eureka_server_2模块中的main方法
4.分别输入http://llynosy1:7001/，http://llynosy2:7002/查看效果。注意修改host文件
5.运行eureka_client模块中的main方法
6.再次查看注册中心