# SpringMvcDemo介绍


## 提纲
0、序言
1、整体介绍  
2、数据库表介绍  
3、项目前后端代码结构介绍  


## 0、序言
大家好，欢迎来到SpringMVCDemo项目主页。
这个项目名称是SpringMvcDemo，它是一个JavaEE初学者入门系列项目中的一个。
JavaEE初学者入门系列项目包括三个项目，它们分别是：ServletJspDemo、SpringMvcDemo、SpringBootDemo。
JavaEE初学者入门系列项目是通过实战向大家介绍Java企业级开发技术的历史演变过程的项目。

Java企业级开发的技术演变历史，是Servlet、Jsp->Spring、SpringMVC->SpringBoot和SpringCloud。
所以这三个项目的目的是通过实战，向大家依次展示Java企业级开发技术的三个发展阶段。
ServletJspDemo项目：展示Servlet、Jsp技术做Java企业级开发的过程。
SpringMvcDemo项目：展示采用Spring、SpringMvc技术做Java企业级开发的过程。
SpringBootDemo项目：展示采用SpringBoot做Java企业级开发的过程。

## 1、整体介绍


SpringMvcDemo项目是一个学习SpringMVC和Spring的示范性项目。它实现的功能是，学生登录系统之后，可以通过课程名称查看本门课程的成绩，老师登录以后可以通过成绩录入界面录入自己所负责课程的成绩。

这个项目可以用来让初学Spring的同学体会Spring的初步使用方法。


2、数据库表介绍
----------------
项目设计了一个SpringMvcDemoDb数据库，3个数据表，分别是student表，用来记录学生的注册信息，teacher表，用来记录老师的注册信息，score表，用来记录学生的成绩。
项目选用了MySQL数据库管理系统作为后台的数据库系统。
具体的数据表中各自字段的设计，可以从schema目录下看到各个表的表结构。

3、项目前后端代码介绍
----------------------
本项目采用MVC模式，前端视图均使用jsp完成，后端分为controller、service、dao、domain四层，controller负责mvc中的c，service、dao等负责mvc中的m。
配置文件采用xml和注解两种方式。

4、建议
--------
如果想看懂这个项目还需要对spring有入门级的了解，因此，建议在看这个项目之前先学习《精通Spring4.x企业应用开发实战》的第一章和第二章，看懂了这两章内容后，看这个项目的代码，之后再看前面的两章内容，这样反复学习之后，至少能对spring有一个清楚明白的入门级了解，会为以后的JavaWeb开发打下良好的基础。
