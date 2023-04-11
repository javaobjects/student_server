# 学生选课管理系统-服务端

#### 介绍
Java SpringBoot 2.6.3 学生选课管理系统
#### 配置环境
1. Jdk1.8.0 161
2. Mysql-5.5.27
3. Apache-maven-3.9.0
#### 开发工具
1. IntelliJ IDEA 2022.3.2
2. Navicat Premium 12
3. Git 2.24.1
#### 开发环境
Windows
#### 安装教程
1.  在navicat中运行数据库脚本生成对应的数据库表
2.  在src/main/resources/application.yml文件里更改数据库名称或数据库密码
3.  在pom.xml文件的父目录运行 mvn clean spring-boot:run 启动后端
#### 包的结构
```agsl
 +- student_server
    +- src
    |   +- main
    |   |    +- java
    |   |    |    +- com
    |   |    |    |    +- augie
    |   |    |    |    |    +- student_server
    |   |    |    |    |    |    +- controller -- 控制器类 负责接收和处理HTTP请求
    |   |    |    |    |    |    +- entity -- 实体类
    |   |    |    |    |    |    +- mapper -- MyBatis框架的数据访问层
    |   |    |    |    |    |    +- service -- 服务类 程序的业务逻辑 与控制器类和数据访问层的服务交互
    |   |    |    |    |    |    +- StudentServerApplication.java -- 应用程序入口类
    |   |    +- resources
    |   |        +- mapper -- MyBatis Mapper XML文件 数据库访问
    |   |        +- application.yml -- 应用程序的配置信息
    |   +- test
    |  	|	+- java -- 测试代码
    +- target -- Maven建项目时自动生成的目录
    +- 数据库脚本
    +- .gitignore -- 指定需要 Git 忽略的文件或目录
    +- LICENSE -- 开源软件的授权协议
    +- pom.xml -- 
    +- README.en.md -- 项目的相关信息文档 英文
    +- README.md -- 项目的相关信息文档
```
#### 拓展知识

1. 请基于后端springboot前端vue写一段前后端通信的示例代码


#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request

#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
