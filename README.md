# PersonalBlog
博客管理



 **[后台入口](https://localhost/Main/Login/Index)** 
后台预览账号/密码：root/123456

#### 介绍
个人博客

#### 软件架构
使用.NET Core 5.0，已集成Redis、Autofac、Mapster映射、FluentValidation验证组件（支持自带model验证）、集成极验行为验证、layui开发

#### 使用说明

1. 网站使用的sqlsugar ORM开源框架，相关文档请查看官网[sqlsugar框架](https://www.donet5.com/)，数据库使用的是mysql，ORM支持7种数据库（MySql、SqlServer、Sqlite、Oracle、Postgresql、达梦、人大金仓），所以可以随意切换，具体请看sqlsugar官网文档
2. 数据库备份以及脚本放在db目录下，执行任意一项即可，数据库表中仅将所有主键统一成“Id”,项目中后台管理员登录用户名/密码:admin/admin1024

