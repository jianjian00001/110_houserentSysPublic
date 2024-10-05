---
### 👉作者QQ ：1556708905 微信：zheng0123Long (支持修改、部署调试、定制毕设)

### 👉接网站建设、小程序、H5、APP、各种系统等

### 👉选题+开题报告+任务书+程序定制+安装调试+ppt 都可以做
---
**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/134351865](https://blog.csdn.net/2303_76227485/article/details/134351865)**

**视频演示：
[https://www.bilibili.com/video/BV1Jw411W7Pe/](https://www.bilibili.com/video/BV1Jw411W7Pe/)**

**毕业设计所有选题地址：
[https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**

## 基于Java+Springboot+Vue的房屋租赁系统小程序(源码+数据库)110

## 一、系统介绍
本系统前后端分离

本系统分为用户、房东、超级管理员三种角色

### 1、用户：
登录、注册、房屋搜索、房屋收藏、看房预约、租房申请、租房记录、看房记录、收藏记录、我的消息、个人信息修改。
### 2、房东：
登录、注册、数据展示、房源列表、在租列表、看房申请管理、租房申请管理、消息查看、个人信息修改。
### 3、超级管理员：
包括房东所有功能、用户管理、图片管理。

## 二、所用技术
后端技术栈：
- Springboot
- SpringMvc
- mybatis
- mysql
- maven

前端技术栈：
- Vue
- elementui
- vue-router
- axios
- 微信小程序

## 三、环境介绍
基础环境 :IDEA/eclipse, JDK 1.8, Mysql5.7及以上, Node.js(14.21), Maven3.6, Vscode, 微信开发者工具

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、管理员页面
![contents](./picture/picture0.png)
![contents](./picture/picture00.png)
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
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
### 2、房东页面
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
### 3、用户页面
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)


## 五、浏览地址
- http://localhost:8080/

超级管理员的账号密码为：admin/123456

房东账号密码为：lisi/123456

## 六、安装教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql
 
2. 使用IDEA/Eclipse导入hrent-api项目，导入时，若为maven项目请选择maven; 等待依赖下载完成

3. 修改resources目录下面application.yml里面的数据库配置和文件路径配置，将wechat-webapp.properties配置文件中的appId和appSecret改为自己的。

4. com/wt/hrentSystem/HrentApplication.java启动后端项目

5. vscode或idea打开hrent-web项目

6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示前台访问地址

7. 微信开发者工具导入hrent-wechat项目,微信开发者工具会自动编译



