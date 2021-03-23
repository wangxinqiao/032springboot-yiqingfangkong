# 032springboot大数据疫情防控系统
032springboot大数据疫情防控系统


#### 介绍
```
springboot高校大数据疫情防控系统，该项目是一个前后端分离的项目。
登录时可选择不同的院校，根据后台展示不同的数据。前端为大屏展示，主要展示数据有返校人数、外省返校人数、境外返校人数、重点观察人数；
疫情监控数据、校园人员分布、预警信息、疫情动态、重点观察人员、热门来源与返校交通、返校人员来源、各个学院返校信息统计等数据。
项目数据直观、界面炫酷，适合java学习及毕业设计等。

```
源码获取：[ **点此获取** ](http://www.shuyue.fun/?type=productinfo&id=187)

#### 环境需要
```
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目 
6.数据库：MySql 5.7版本；
```

#### 系统框架
```
1.后端：SpringBoot
2.前端：Echarts、JQuery
```


#### 使用说明
```
1. 使用IDEA/Eclipse/MyEclipse导入后端项目源码，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
2. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
3. 运行项目前，需要配置好MqSQL数据库，在application.properties中修改数据库对应的配置文件；
4. 配置Tomcat,在Tomcat中运行后端项目;
4. 找到前端目录，双击login.html 进入主页面，选择山东英才学院，账号:sdyc 密码:123456
```

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/163212_28a7dd91_863230.png "QQ20210310-170930@2x.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/163244_7ee97d94_863230.png "屏幕截图.png")
