<p align="center">
  <h3 align="center">谱源API开放平台</h3>
  <h4 align="center">YiPortApi前端项目</h4>
  <p align="center">
    <a href="https://github.com/YiPort/yp_api"><strong>YPApi后端项目 »</strong></a>
    <br/>
    <a href="https://github.com/YiPort/yp_api_frontend"><strong>YPApi前端项目 »</strong></a>
    <br/>
  </p>

--- 

## 项目简介
此项目是 [前端项目](https://github.com/YiPort/yp_api_frontend) ，请搭配 [后端项目](https://github.com/YiPort/yp_api) 使用。
一个提供 API 接口供开发者调用的平台。
管理员可以接入并发布接口，统计分析各接口调用情况；用户可以注册登录并开通接口调用权限，然后可以浏览接口及在线调试，还能使用客户端 SDK 轻松在代码中调用接口。

## 技术选型
- [前端项目](https://github.com/YiPort/yp_api_frontend)
    - Ant Design Pro
    - React
    - Ant Design Procomponents
    - Umi
    - Umi Request (Axios的封装)

- [后端项目](https://github.com/YiPort/yp_api)
    - Java
    - Spring Boot
    - MySQL 数据库
    - MyBatis-Plus 及 MyBatis X 自动生成
    - API 签名认证（Http 调用）
    - Spring Boot Starter（SDK 开发）
    - Dubbo 分布式（RPC、Nacos）
    - Spring Cloud Gateway 微服务网关
    - Hutool、Apache Common Utils、Gson 等工具库
## 如何使用

### 1.安装 `node_modules`
>npm install

或者
>yarn

### 2.启动项目
**启动命令**
>npm run start:dev

除了启动命令，下面提供了一些有用的脚本，以帮助您快速启动和建立与 Web 项目，代码样式检查和测试。
**启动项目**
>Start project

**构建项目**
>npm run build

**检查代码风格**
>npm run lint

**您还可以使用 script 自动修复一些初始化错误**
>npm run lint:fix

**测试代码**
>npm test
