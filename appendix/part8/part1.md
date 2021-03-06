<!-- toc -->

# 代码规范标准

# 订立的代码规范：

## 代码排版：
        
### 关键词和操作符之间加适当的空格。 

### 函数或过程的开始、结构的定义及循环、判断等语句中的代码都要采用缩进风格。 

## 命名规范：
        
### 变量以 小驼峰法 方式进行命名；
                
> 除第一个单词之外，其他单词首字母大写。

> 举例：用户名称 为 userName

### angularJS中的模型必须以 小驼峰法 命名，必须以 Model作为后缀；

> 举例：账号的Model 为 accountModel

## 文件名命名规范：

### Controller文件名命名规则：以 小驼峰法 命名，名称格式： 功能+Controller.js；

> 举例： 登录的Controller 为 loginController.js

### service 文件名命名规则：以 小驼峰法 命名，名称格式： 功能+.service.js

> 举例： 网络请求服务 为 net.service.js

### html 文件名命名规则：以 小驼峰法 命名，名称格式： 功能+.html

> 举例： 登录的html 为 login.html

## 平台基础知识掌握程度：（待定）

### make.json的作用，keystore 文件夹的作用

### data.zip的作用及生成方式

# CSS规范标准

## css 文件名命名规则：以 小驼峰法 命名，名称格式： 功能+.css

> 举例： 登录的css 为 login.css

## 页面布局采用相对布局方式

## 控件布局基准

* 距离父容器顶部距离小的控件，以父容器顶部为基准

* 距离父容器底部距离小的控件，以父容器底部为基准

* 距离父容器左边框距离小的控件，以父容器左边框为基准

* 距离父容器右边框距离小的控件，以父容器右边框为基准

## 所有第一级子控件均以ion-content为父容器作为基准进行布局

* 特殊点：页面适配到iOS平台时，导航栏的高度为64像素。所以氛围两种情况；

    * 无导航栏页面，查看设计师给的UI标注图时，ion-content的子控件距离屏幕顶部，为80像素时，该子控件应该距离ion-content容器的顶部距离为16像素。禁止以屏幕顶部为基准进行UI布局。
    
    * 有导航栏页面，查看设计师给的UI标注图时，ion-content的子控件距离导航栏底部距离为30像素，那么该子控件距离ion-content容器的顶部设置为30像素。
   
* 页面适配到Android平台，待定

# 评审时间：

## 每周三内部评审

## 每周五项目组评审