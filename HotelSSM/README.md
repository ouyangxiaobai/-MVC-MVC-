# 项目名称

基于MVC模式的多视类技术的应用研究（基于MVC的酒店预订系统)+论文+开题报告+包安装+包讲解

# 系统介绍
4系统设计

4.1 系统模块设计
4.1.1 登陆模块

必须输入自己的设置的用户名和设置，否则填错或输入空白都将给出提示是错误的信息。

4.1.2 管理员模块

系统管理：整个系统的全方面数据和菜单信息的管理。

用户管理：用户的增删改查操作。

系统日志管理：查询系统的登录日志。

楼层管理：酒店楼层的统一维护。

房型管理：对系统的房型进行管理例如：单人间、大床房、标准间等。

房间管理：酒店房间的信息维护。

客户管理：客户个人信息的维护。

预订管理：查看前台用户的预订信息。

入住管理：管理系统的用户入住情况。

统计报表：分别从月以及日来统计系统的经营情况。

4.1.3 前台模块

房间状态模块：房间信息，预订操作，个人信息模块：实现了对于当前登陆用户的信息查看和密码修改、查看订单信息。

# 环境需要

1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。\
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;\
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可\
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS； \
5.数据库：MySql 5.7版本；\
6.是否Maven项目：否；

# 技术栈

1. 后端：Spring+SpringMVC+Mybatis\
2. 前端：JSP+CSS+JavaScript+jQuery

# 使用说明

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；\
2. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;\
若为maven项目，导入成功后请执行maven clean;maven install命令，然后运行；\
3. 将项目中springmvc-servlet.xml配置文件中的数据库配置改为自己的配置;\
4. 运行项目，在浏览器中输入http://localhost:8080/ 登录

# 高清视频演示

https://www.bilibili.com/video/BV1BL4y1N7em/

> # **数据库及资料有偿获取：QQ:3484724101**

​