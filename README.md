# init-manage
  基于SpringBoot2.x的初始化管理平台
## 技术架构：
  后端技术|前端技术|模版引擎|组件
  ---|---|---|---
  springboot2.x|layui|thymeleaf|echarts
  TKmybatis|vue2.x||
  redis|||
  shiro|||
## 项目结构：
```
|-- src
  |-- main
    |-- java
      |-- com
        |-- y4l3
          |-- platform
            |-- common                        // 公共类目录
            |-- configurer                    // 配置器目录
            |-- main                          // 登录、登出等
            |-- moudle                        // 业务模块
            |-- platformApplication.java      // 项目加载入口类
  |-- resources                               // 资源文件目录
    |-- mapper                                // mybatis数据库映射文件
    |-- static                                // 静态文件
    |-- templates                             // HTML页面
    |-- application-dev.yml                   // 开发环境配置文件
    |-- application-pro.yml                   // 正式环境配置文件
    |-- application.yml                       // 项目主配置文件
    |-- logback-spring.xml                    // logback日志配置
|-- pom.xml
```
## 主要功能
  - 首页
  - 系统管理
    - 用户管理
    - 菜单管理
    - 角色管理
  - 应用程序
  - 操作日志
## 功能截图
  ![image](https://github.com/iam286/init-manage/blob/master/picture/login.jpg)
