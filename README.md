# springcloud-learning

<p>
<a href="#公众号"><img src="http://macro-oss.oss-cn-shenzhen.aliyuncs.com/mall/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-macrozheng-blue.svg" alt="公众号"></a>
<a href="https://github.com/macrozheng/mall"><img src="http://macro-oss.oss-cn-shenzhen.aliyuncs.com/mall/badge/%E5%90%8E%E5%8F%B0%E9%A1%B9%E7%9B%AE-mall-blue.svg" alt="后台项目"></a>
<a href="https://github.com/macrozheng/mall-admin-web"><img src="http://macro-oss.oss-cn-shenzhen.aliyuncs.com/mall/badge/%E5%89%8D%E7%AB%AF%E9%A1%B9%E7%9B%AE-mall--admin--web-green.svg" alt="前端项目"></a>
</p>

## 简介

一套实用的SpringCloud系列教程，涵盖了大部分核心组件的使用，基于最新的Greenwich版本。

## 目录

- [Spring Cloud 整体架构概览](https://juejin.im/post/5d764f05e51d4561fb04bfd7)
- [Spring Cloud Eureka：服务注册与发现](https://juejin.im/post/5d78cd53f265da03d55e8351)
- [Spring Cloud Ribbon：负载均衡的服务调用](https://juejin.im/post/5d7f9006f265da03951a260c)
- [Spring Cloud Hystrix：服务容错保护](https://juejin.im/post/5d822d27e51d45621479ad92)
- [Hystrix Dashboard：断路器执行监控](https://juejin.im/post/5d88cb58f265da03e4679eff)
- [Spring Cloud OpenFeign：基于Ribbon和Hystrix的声明式服务调用](https://juejin.im/post/5d9c85c3e51d45782c23fab6)
- [Spring Cloud Zuul：API网关服务](https://juejin.im/post/5d9f2dea6fb9a04e3e724067)
- [Spring Cloud Config：外部集中化配置管理](https://juejin.im/post/5da4709af265da5baa5b06ac)
- [Spring Cloud Bus：消息总线](https://juejin.im/post/5da70d1351882509615bea34)
- [Spring Cloud Sleuth：分布式请求链路跟踪](https://juejin.im/post/5dadb4d36fb9a04e02409a7d)
- [Spring Cloud Consul：服务治理与配置中心](https://juejin.im/post/5db05582f265da4d4c20180f)
- [Spring Cloud Gateway：新一代API网关服务](https://juejin.im/post/5db6eed6518825644076d0b6)
- [Spring Boot Admin：微服务应用监控](https://juejin.im/post/5db98a2d518825649c730f81)

## 项目结构

``` lua
springcloud-learning
├── eureka-server -- eureka注册中心
├── eureka-security-server -- 带登录认证的eureka注册中心
├── eureka-client -- eureka客户端
├── user-service -- 提供User对象CRUD接口的服务
├── ribbon-service -- ribbon服务调用测试服务
├── hystrix-service -- hystrix服务调用测试服务
├── turbine-service -- 聚合收集hystrix实例监控信息的服务
├── hystrix-dashboard -- 展示hystrix实例监控信息的仪表盘
├── feign-service -- feign服务调用测试服务
├── zuul-proxy -- zuul作为网关的测试服务
├── config-server -- 配置中心服务
├── config-security-server -- 带安全认证的配置中心服务
├── config-client -- 获取配置的客户端服务
├── consul-config-client -- 用于演示consul作为配置中心的consul客户端
├── consul-user-service -- 注册到consul的提供User对象CRUD接口的服务
├── consul-service -- 注册到consul的ribbon服务调用测试服务
├── api-gateway -- gateway作为网关的测试服务
├── admin-server -- admin监控中心服务
├── admin-client -- admin监控中心监控的应用服务
└── admin-security-server -- 带登录认证的admin监控中心服务
```

## 公众号

mall项目全套学习教程连载中，**关注公众号**第一时间获取。

![公众号图片](http://macro-oss.oss-cn-shenzhen.aliyuncs.com/mall/banner/qrcode_for_macrozheng_258.jpg)
