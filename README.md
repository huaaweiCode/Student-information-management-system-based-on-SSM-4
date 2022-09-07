# 基于SSM的学生信息管理系统（简单版）



## 1、项目介绍

学生信息管理系统拥有两种角色，分别为学生和管理员，可以作为初学者使用学习。

**学生**：个人信息查看和修改、查看班级信息

**管理员**：管理员对学生信息、老师信息、学院年级信息的添加、修改、删除、多条件查询等功能

## 2、项目技术

后端框架：SSM（Spring、SpringMVC、Mybatis）

前端框架：easyui、layui、jsp

其它：mysql5-8、tomcat8-10、JDK1.8+

## 3、开发工具

Eclipse、idea和myEclipse都可以

## 4、功能介绍及视频演示

- 登录页面
  ![登录](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515110650.PNG)
  学生管理系统的中两种用户均可以通过此界面登录，系统将自动识别用户类型，经过密码和验证码正确性验证之后，将会跳转到不同的页面

- 管理员界面-学生列表
  ![管理员-学生列表](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515110656.PNG)
  管理员可以添加、修改和删除学生信息，点击添加按钮，页面将会跳出添加学生页面，输入相关信息之后，便可将学生信息保存到数据库中。此外，管理员还可以通过学生名字、所属班级等条件查找学生。

- 管理员界面-年级列表
  ![管理员-年级列表](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515110703.PNG)

管理员可以添加、修改和删除年级信息。点击添加按钮，页面将会跳出添加年级的页面，输入相关信息之后，便可将年级信息保存到数据库中。此外，管理员还可以通过年级名字查找相关信息。班级信息和用户信息同上。

- 学生界面-个人信息界面
  ![学生修改个人信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/20220515110714.PNG)

学生可以查看班级通讯录以及个人的信息，并能够对个人信息进行修改，如上图点击“提交”按钮后，便可将数据更新到数据库中。

