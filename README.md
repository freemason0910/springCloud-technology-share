# springCloud-technology-share

阴阳引，覆阴阳。乾坤锁，锁乾坤。

## 作者简介
&emsp;&emsp;我是一个宅男；技术宅男。从参加工作以来一直从事代码相关工作，混迹在java生态圈，对新技术有好奇心。也算是全栈工程师了；写下这个项目只是为了记录自己对技术架构的见解、和踩过的坑点。关于技术架构我做的还是很初级的事情！分析的都是自己的心得。希望看到的人不要心里骂我就好了，同为天涯沦落人，相逢何必曾相识。
## 项目简介

&emsp;&emsp;在学习、应用springCloud的的过程中，踩过的一些坑；应对方案，分享给大家！有很多的更优秀的解决方
案我也许还不知道！我只是把我知道的写下来;<br/>
&emsp;&emsp; 在这次的实践中采用微服务设计；接口采用rest风格接口，微服务的好处和缺点还是有必要说明一下的：

## 技术栈
- spring boot
- mybatis
- spring cloud
- node.js
- redis
- auth2.0

## 架构说明
&emsp;&emsp;简单描述一下业务场景：<br/>
在公司性质是一家金融公司，有很多子公司，每个子公司每个月都有大量的财务工作要做，所以公司领导要求做一个财务共享系统，为的是能够将各个分公司的财务集中管理；也就是说全国各地的子公司没必要每家有财务人员；每家公司的职员到了时间；将账上传至系统；再由公司统一的财务中心来处理这些账目；
<br/>
 &emsp;&emsp;基于上面地描述的应用场景；我们可以将系统做成一个all-in-one的系统，也可以是一个垂直系统，也可以是一个微服务系统；在架构的选择上我们进行了一些考量：
 - 1、all-in-one 架构简单，初期生产性高，但是不易后期升级、扩展。
 - 2、垂直架构
 - 3、微服务架构
 
 ## 目录
- [技术栈各技术简介]()
- [整体架构介绍]()
- [前端node.js koa的实际应用]()
- [网关zuul的应用]()
- [权限认证过程]()
- []()
- []()