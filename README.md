# 全目录

[更多系统、论文，供君选择 ~~>](https://www.bitwise.net.cn)

# 95.SupermarketCashierManagementSystem

<p>群: 983063232(入群获取sql文件)</p>
<p>QQ: 206157502(加好友获取sql文件)</p>


<p><h1 align="center">95.超市收银管理系统</h1></p>

<p align="center">
	<img src="https://img.shields.io/badge/jdk-1.8-orange.svg"/>
    <img src="https://img.shields.io/badge/springboot-3.x-blue.svg"/>
    <img src="https://img.shields.io/badge/mavne-3.x-blue.svg"/>
    <img src="https://img.shields.io/badge/html-3.x-blue.svg"/>
</p>


# 简介

> 本代码来源于网络,仅供学习参考使用,请入群(983063232)后联系群主索要sql文件!
>
> 提供1.远程部署/2.修改代码/3.设计文档指导/4.框架代码讲解等服务
>
> 前台首页: http://localhost:8080/login
>
> 用户: root   密码: 123456


# 环境

- <b>IntelliJ IDEA 2009.3</b>

- <b>Mysql 5.7.26</b>

- <b>Tomcat 7.0.73</b>

- <b>JDK 1.8</b>

#### 项目功能
本系统是基于B/S架构的超市管理系统，为了解决超市对雇员，对商品的管理，提高工作效率而开发。
本系统具有收银记录出纳的功能，记录超市的流水、销售统计功能，可以分类查询某时间段某具体产品的收益，售出情况，对商品进行分类管理，系统可以管理分类，增加分类，修改分类信息，删除分类，可以对商品库存进行管理，实现对商品的模糊查询，分类查询，按生产日期查询，并能对商品进行添加库存，还可以新建商品，修改商品属性，删除商品，此外还有过滤器对访问权限的管理，只有登录系统才可以访问系统页面。

#### 项目用户
超市人员：收银员、理货员、仓库管理员、采购员

#### 软件架构
BS架构
```
后端 SpringBoot+Maven+Mysql+Shiro+Redis
前端 Bootstrip+Echarts+Thymeleaf+Ajax
手机端扫码枪 uni-app
```

#### 功能分析

#####  用户管理

##### 权限管理

##### 收银管理

##### 商品管理

##### 库存管理

##### 单据管理

##### 销售分析

```json
    //二维码数据
    {
        "api":"/code/confirm", //哪个接口
        "bindPage":true, //是否是绑定扫码枪的条码
        "des":"謾ｶ體ｶ謇ｫ遐∫ｻ大ｮ壽沖遐∵棯",
        "nextType":"sy", //真实条码存储的位置
        "no":"6468C99E4CFE96DE5882576226C460E2",//当前二维码是哪个用户
        "type":"jssy", //哪个页面的二维码
        "url":"http://192.168.10.68:8080" //服务器端的地址
    }
```

#### 使用说明

二维码生成
文件位置项目 resources/lib

```
安装
mvn install:install-file -Dfile=e:\QRCode-3.0.jar -DgroupId=QRCode -DartifactId=QRCode -Dversion=3.0 -Dpackaging=jar 
```




## 缩略图

![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/5fd2b2cc-1442-49f6-93ef-1dd36ccfc55b.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/19b47e7b-eb48-4985-8fd2-98e4b25c0860.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/dafb1d2f-1400-4818-9d81-88dcd6d2619b.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/d1d6d7df-71b9-4c2e-b149-b092e73f267b.png)
![](https://bitwise.oss-cn-heyuan.aliyuncs.com/2024/9/10/ff61957a-ecb4-421c-84f7-9507611c4327.png)





