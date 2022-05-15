

## 简介

Doing Fast以“避免重复造轮子，善于用已有轮子来造车”为出发点，努力将软件开发人员从重复、繁琐且易出错的工作中解脱出来，大大提高企业项目的开发效率。

Doing Fast是项目中“util”包/“common”包友好的替代，它节省了开发人员对项目中公用类和公用工具方法的封装时间，使开发专注于业务，同时可以最大限度的避免封装不完善带来的bug。

最终打造出一套风格统一、易于调用的工具服务，工具多种多样，涵盖实际开发过程中的方方面面。

## 包含组件

一个Java基础工具类，对文件、流、加密解密、编码解码、正则等JDK方法进行封装，组成各种Util工具类，同时提供以下组件：

| 主要模块          | 介绍                                                         |
| ----------------- | ------------------------------------------------------------ |
| doing-fast-aop    | JDK动态代理封装，提供非IOC下的切面支持                       |
| doing-fast-cache  | 简单缓存实现                                                 |
| doing-fast-core   | 核心工具模块，包括注解操作、Bean操作、日期操作、文件操作、克隆操作、<br/>单例对象管理、类型转换操作、各种Util等等 |
| doing-fast-crypto | 加密解密模块，提供对称、非对称和摘要算法封装                 |
| doing-fast-poi    | 针对Apache poi进行二次封装，方便使用                         |

## 如何应用

> 如果你的项目使用是Maven构建的，加入Doing Fast的依赖即可：

在项目的pom.xml的dependencies中加入以下内容：

````xml
        <dependency>
            <groupId>com.zzuli</groupId>
            <artifactId>doing-fast-starter</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency>
````

> 如果你是普通的java项目，可通过下载jar包方式应用：

第一步：

![image-20220514182036349](/images/jar引入项目-1.png)

第二步：

![image-20220514182036349](/images/jar引入项目-2.png)
