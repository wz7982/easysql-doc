## 概述：

easysql是一个使用Kotlin语言编写的轻量级orm框架，使用接近于原生sql的dsl构建跨数据库的sql语句，无需xml配置，就能构造出复杂的查询。

功能包括但不限于：增删改查，创建删除表和索引。

支持完整的对象映射，但也可以使用非对象映射方式构建sql，这一点与上文中的DDL构建功能共同为用户提供灵活的动态建表查询功能。

使用druid <https://github.com/alibaba/druid> 中的ast模块构建sql语法树，**在此感谢温绍锦先生和他的团队开发出了如此优秀的跨数据库sql parser。**

本项目托管在github网站上，网址为：<https://github.com/wz7982/easysql/>