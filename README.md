大象项目！！



技术架构：
-----------------------------------

#### 后端
- 基础框架：Spring Boot 2.0.3.RELEASE

- 持久层框架：Mybatis-plus_3.0.6

- 安全框架：Apache Shiro 1.4.0-RC2，Jwt_3.4.1

- 数据库连接池：阿里巴巴Druid 1.1.10

- 缓存框架：redis

- 日志打印：logback

- 其他：fastjson，poi，Swagger-ui，quartz, lombok（简化代码）等。


#### 前端
 
- [Vue 2.5.22](https://cn.vuejs.org/),[Vuex](https://vuex.vuejs.org/zh/),[Vue Router](https://router.vuejs.org/zh/)
- [Axios](https://github.com/axios/axios)
- [ant-design-vue](https://vuecomponent.github.io/ant-design-vue/docs/vue/introduce-cn/)
- [webpack](https://www.webpackjs.com/),[yarn](https://yarnpkg.com/zh-Hans/)
- [vue-cropper](https://github.com/xyxiao001/vue-cropper) - 头像裁剪组件
- [@antv/g2](https://antv.alipay.com/zh-cn/index.html) - Alipay AntV 数据可视化图表
- [Viser-vue](https://viserjs.github.io/docs.html#/viser/guide/installation)  - antv/g2 封装实现
- eslint，[@vue/cli 3.2.1](https://cli.vuejs.org/zh/guide)
- vue-print-nb - 打印

#### 开发环境

- 语言：Java 8

- IDE(JAVA)： Eclipse安装lombok插件 或者 IDEA

- IDE(前端)： WebStorm 或者 IDEA

- 依赖管理：Maven

- 数据库：MySQL5.0  &  Oracle 11g

- 缓存：Redis




 

### 功能模块
```
├─系统管理
│  ├─用户管理
│  ├─角色管理
│  ├─菜单管理（权限设置）
│  ├─部门管理
│  └─字典管理
├─智能化功能
│  ├─代码生成器功能（一键生成，包括前端页面也可以生成，绝对是后端开发福音）
├─系统监控
│  ├─定时任务
│  ├─系统日志
│  ├─系统通知
│  ├─SQL监控
│  ├─swagger-ui(在线接口文档)
│─常用示例
│  ├─单表模型例子
│  └─一对多模型例子
│  └─打印例子
│  └─一对多TAB例子
│─更多页面模板
│  ├─各种高级表单
│  ├─各种列表效果
│  └─结果页面
│  └─异常页面
│  └─个人页面
└─其他模块
   └─其他
   
```
   
   






后台开发环境和依赖
----
- java
- maven
- jdk8
- mysql
- redis
- 数据库脚步：jeecg-boot\docs\dbsys-init-20190225.sql
- 默认登录账号： admin/123456


前端开发环境和依赖
----
- node
- yarn
- webpack
- eslint
- @vue/cli 3.2.1
- [ant-design-vue](https://github.com/vueComponent/ant-design-vue) - Ant Design Of Vue 实现
- [vue-cropper](https://github.com/xyxiao001/vue-cropper) - 头像裁剪组件
- [@antv/g2](https://antv.alipay.com/zh-cn/index.html) - Alipay AntV 数据可视化图表
- [Viser-vue](https://viserjs.github.io/docs.html#/viser/guide/installation)  - antv/g2 封装实现



