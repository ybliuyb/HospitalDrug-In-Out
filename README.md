# 医院药品出入库管理系统

## 介绍
系统主要实现了供应商信息和药品信息的增、删、改、查、导入、导出的基本信息管理功能，以及药品入库、出库、退回和库存的管理功能，其中 药品入库时能实时的展示药品到期时间及对即将要过期和已过期药品进行系统 警告提示。
系统有药品管理员和超级管理员两种角色，药品管理员能管理药品，超级管理员除药品外还能进行用户管理，部门管理等以及日志查看管理。



## 系统环境版本说明

JDK >= 1.8 

Mysql >=8.0

Redis >= 3.0

Maven >= 3.0

Node >= 12

## 使用说明

1、后端运行：

(1)将项目导入到IntelliJ IDEA中

(2)创建数据库ly，并执行ly.sql数据脚本

(3)修改数据库连接，编辑resources目录下的application-druid.yml，将数据库账号密码改为自己本地的

(4)配置redis编辑resources目录下的application.yml，可配置redis（默认无密码）

(5)启动redis后，再启动RuoYiApplication.java即可运行系统。

2、前端运行：

(1)cd ruoyi-ui

(2)使用npm install安装依赖（不建议通过cnpm或其它进行安装 可能会丢包）

(3)在终端使用npm run dev来启动项目

## 仓库代码为若依框架！学习若依可下载。



## 作者QQ： 1310843283，想白嫖勿加！想白嫖勿加！想白嫖勿加！



## 想毕业还不想花钱的也勿加！

## 系统演示

### 登录（验证码功能已关闭，可参考若依开启验证码功能）。

超级管理员： `admin` `admin123` 普通管理员：`ry`  ` admin123`



登录包括两种不同的风格，一种是背景图，一种是`three.js`粒子动效。默认样式为背景图，若要更换则将`src/views/login1.vue`和`login.vue`文件名进行更改，让你想使用的样式的文件名为`login.vue`则可。（两个文件只能有一个名为`login.vue`,那个名为login.vue则就是那个样式）

![登录](yanshitu/login.png)
![登录](yanshitu/login1.png)

### 首页


![首页](yanshitu/shouye.png)

#### 	 首页2

![首页](yanshitu/shouye1.png)

### 药品管理

####    药品供应商管理  

![药品供应商管理](yanshitu/gongyingshang.png)

####  药品信息管理

![药品信息管理](yanshitu/xinxi.png)

![药品信息详情](yanshitu/xinxidetail.png)

####    药品入库管理（新增批量入库功能，未更新演示图）

![药品入库管理](yanshitu/ruku.png)

#### 药品出库管理

![药品出库管理](yanshitu/chuku.png)

#### 药品库存管理

![药品库存管理](yanshitu/kucun.png)

##### 药品出售

![首页](yanshitu/chushou.png)

##### 药品批量出售

![首页](yanshitu/piliangchushou.png)



##### 药品流水

![药品流水](yanshitu/liushuizhang.png)  

#### 订单管理

![首页](yanshitu/dingdan.png)

##### 订单明细

![首页](yanshitu/dingdanmingxi.png)

##### 取消订单

![首页](yanshitu/quxiaodingdan.png)

####  药品回退管理

![药品退回管理](yanshitu/tuihui.png)

### 系统集成了积木报表（详情请访问积木[报表官网](http://www.jimureport.com/)）

![积木报表](yanshitu/jimu.png)

#### 药品入库报表

![药品入库报表](yanshitu/rukubaobiao.png)

### 系统管理和日志管理模块为[若依系统](http://www.ruoyi.vip/)模块。
