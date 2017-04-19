% Qcon 分享
% 张凯
% 2017 年 4 月 17 日

# 微服务的模式语言

## 单体应用

![][monolithic_architecture]

## 缺点

- 随着时间推移，应用会越来越大，越来越复杂，造成：
    - 难以完全理解
    - 难以敏捷开发
    - 难以敏捷部署

- 将来难以更换技术栈

## 微服务

![][microservice_architecture]

## 利于持续交付/部署

![][cd_microservice]

## 更小，更简单的应用

- 易于理解和开发
- 可以更快地构建和部署
- 更短的启动时间
- 更好地隔离错误
- 更灵活的技术栈

## 易于扩展

![][clear_responsibility]

## 微服务不是银弹

- 开发分布式系统的复杂性
- 测试分布式系统的复杂性
- 部署和操作分布式系统的复杂性 -> PaaS
- 开发和部署横跨多个服务的特性需要审慎的协调
- 要使用多个数据库，并进行事务管理以保证最终的一致性

## 微服务模式语言

![][microservice_pattern]

## 部署框架

![][deployment_architecture]

## 解耦方法

![][decomposition]

## 部署方式

![][deployment]

## 通信

![][communication]

## 服务发现

![][service_discovery]

## 基础服务

![][chassis]

## 数据一致性

![][data_consistency]

## 查询

![][cqrs]

## 监控

![][monitor]

[monolithic_architecture]: images/monolithic-architecture.png { width=80% }
[microservice_architecture]: images/microservice-architecture.jpg { width=60% }
[cd_microservice]: images/cd-microservice.jpg { width=50% }
[clear_responsibility]: images/clear-responsibility.jpg { width=60% }
[microservice_pattern]: images/microservice-pattern-language.jpg { width=60% }
[deployment_architecture]: images/deployment-architecture.jpg { width=60% }
[decomposition]: images/decomposition.jpg { width=60% }
[deployment]: images/deployment.jpg { width=60% }
[communication]: images/communication.jpg { width=60% }
[service_discovery]: images/registration.jpg { width=60% }
[chassis]: images/chassis.jpg { width=60% }
[data_consistency]: images/data-consistency.jpg { width=60% }
[cqrs]: images/cqrs.jpg { width=60% }
[monitor]: images/monitor.jpg { width=60% }
