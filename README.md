## 本项目完整源码是收费的  接毕业设计和论文

### 作者微信：grapro666 QQ：3642795578 (支持部署调试、支持代做毕设)

### 接javaweb、python、小程序、H5、APP、各种管理系统、单片机、嵌入式等开发

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/144816488](https://blog.csdn.net/2303_76227485/article/details/144816488)**

**视频演示：
[https://www.bilibili.com/video/BV1xVC6YBEWP/](https://www.bilibili.com/video/BV1xVC6YBEWP/)**

**毕业设计所有选题地址：
[https://github.com/codegitpro/allProject](https://github.com/codegitpro/allProject)**

## 基于Java+Springboot+vue3的重修课程信息管理系统(源代码+数据库)204

## 一、系统介绍
本项目前后端分离(可以改为ssm版本)，分为用户、教师、管理员三种角色
### 1、用户：
- 登录、公告查询、重修课程查询、课程成绩查询、建议报告查询、重修申请管理、个人信息、密码修改
### 2、教师：
- 学生查询、成绩录入、成绩查询、报告管理、重修课程管理、重修申请管理、个人信息、密码修改
### 3、管理员：
- 班级管理、专业管理、用户管理(导入导出)、建议报告管理、课程成绩管理、重修课程管理、系统公告管理、重修申请管理

## 二、所用技术
后端技术栈：
- Springboot
- mybatisPlus
- Mysql
- Maven

前端技术栈：
- Vue3
- Vue-router
- axios
- elementPlus

## 三、环境介绍
基础环境 :IDEA/eclipse, JDK1.8, Mysql5.7及以上, Maven3.6, node14, navicat

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、用户：
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
### 2、教师：
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
### 3、管理员：
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)

## 五、浏览地址
后台地址：http://localhost:8081

用户账号密码：学号1/123456

教师账号密码：教师工号1/123456

管理员账户密码：admin/admin


## 六、部署教程
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件

2. 使用IDEA/Eclipse导入server_code项目，若为maven项目请选择maven，等待依赖下载完成

3. 修改application.yml里面的数据库配置,src/main/java/com/SpringbootSchemaApplication.java启动后端项目

4. vscode或idea打开manage_code后台项目

5. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run serve,执行成功后会显示访问地址