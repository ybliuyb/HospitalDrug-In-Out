# 医院药品出入库管理系统（不限于药品出入库，该系统可改成各种出入库系统毕设）

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

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/3d2a43d9-4a17-4938-ba3b-20fa5bb78f7f)
![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/4b58e375-6f5d-417b-868d-75435b11adb7)


### 首页


![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/dae76f75-6384-42d9-b8ce-f3b38408fce6)

#### 	 首页2

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/a0ba7960-ee1f-4e5d-8bbc-7fe609ba21f0)

### 药品管理

####    药品供应商管理  

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/7ef8f015-666a-4e9c-9ada-20bcaa748842)

####  药品信息管理

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/719b0ef1-7310-4135-9437-cf1341a5bc0a)

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/775f50a8-5f01-4bd1-b0c4-5396efd4f665)

####    药品入库管理（新增批量入库功能，未更新演示图）

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/a133b3a6-fdf3-470a-ad1a-e7baa484a2a0)

#### 药品出库管理

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/1b94de5b-458d-465a-8884-ccb55cf62df4)

#### 药品库存管理

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/bc2e2bbc-92a1-43b9-8948-05cacf42777c)
##### 药品出售

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/84a90fd5-7e5b-4651-8545-02451089813c)

##### 药品批量出售

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/1f78d4a2-414e-468f-85ea-5cab35397b21)



##### 药品流水

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/6111ae40-13ad-474d-9c97-2f6d3b37666d)

#### 订单管理

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/8e7415ca-3bdd-4c24-9fde-3be199e411e1)

##### 订单明细

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/0b4117a9-45db-41ac-98f3-2b218c6fcae8)

##### 取消订单

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/59110319-0c69-4760-8165-abfe281d8ff7)

####  药品回退管理

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/8bdcb16c-d483-46c2-a035-a6e19685dbc4)

### 系统集成了积木报表（详情请访问积木[报表官网](http://www.jimureport.com/)）

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/d0266ba7-5108-4c9c-9343-a7cd48ee58c9)

#### 药品入库报表

![image](https://github.com/ybliuyb/HospitalDrug-In-Out/assets/99953375/ecdcd767-f9a9-4a5e-9a56-db58a5255563)

### 系统管理和日志管理模块为[若依系统](http://www.ruoyi.vip/)模块。
