# SpringBootDMS
【毕业设计】基于Spring Boot的宿舍管理系统(Dormitory Management System)。以MySQL为数据库，在Spring Boot + SpringMVC + MyBatis + Layui框架下基于B/S架构设计开发而成。

文件夹介绍：
  * `database`中存放的是sql文件
  * `dormitory`中存放的是后端代码
  * `dormitoryfront`中存放的是前端代码
  * `excel`中存放的是系统运行时文件上传部分可能用到的Excel文件

# 一、项目介绍💁🏻
基于Spring Boot的宿舍管理系统是我所完成的本科毕业设计，现在将它分享出来，与大家互相交流、学习。欢迎小伙伴们留下评论~

系统以[MySQL](https://dev.mysql.com/downloads/mysql/) 8.0.23为数据库，在[Spring Boot](https://spring.io/projects/spring-boot) + [SpringMVC](https://spring.io/) + [MyBatis](https://mybatis.org/mybatis-3/zh/index.html) + [Layui](https://www.layui.com/)框架下基于B/S架构设计开发而成。系统中的用户分为三类，分别为学生、宿管、后勤。这三类用户拥有不同的操作权限。

系统中用到的技术包括[Axios](http://www.axios-js.com/zh-cn/docs/), [Echarts](https://echarts.apache.org/zh/index.html), [POI](https://poi.apache.org/), [JWT](https://jwt.io/)等等。特色功能有人性化的宿舍分配，可视化的账单管理、房间管理、记账管理，Excel文件上传后数据导入数据库等等。

## 1. 功能模块
系统的功能模块图如下图所示。
<img src="https://img-blog.csdnimg.cn/20210514161117417.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1NoZXJsb29vY2s=,size_16,color_FFFFFF,t_70#pic_center" width="100%">


## 2. E-R图
系统的E-R图如下图所示。
<img src="https://img-blog.csdnimg.cn/20210514161213124.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1NoZXJsb29vY2s=,size_16,color_FFFFFF,t_70#pic_center" width="100%">


##  3. 页面效果
系统的部分功能模块页面如下所示。
<img src="https://img-blog.csdnimg.cn/20210514161411550.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1NoZXJsb29vY2s=,size_16,color_FFFFFF,t_70#pic_center" width="100%">
<img src="https://img-blog.csdnimg.cn/20210514161505403.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1NoZXJsb29vY2s=,size_16,color_FFFFFF,t_70#pic_center" width="100%">
<img src="https://img-blog.csdnimg.cn/20210514161647802.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1NoZXJsb29vY2s=,size_16,color_FFFFFF,t_70#pic_center" width="100%">
<img src="https://img-blog.csdnimg.cn/20210514161706414.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L1NoZXJsb29vY2s=,size_16,color_FFFFFF,t_70#pic_center" width="100%">

# 二、运行视频📹
了解更多关于系统的运行效果，可以点击下方观看演示视频

[👉🏻系统演示视频]()
<font color=gray size=2>亲测，值得一看~</font>

# 三、运行教程
若下载源码后不知如何顺利运行，请参考[运行教程](https://blog.csdn.net/Sherlooock/article/details/116795048)（文章第三部分）
