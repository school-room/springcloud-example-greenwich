# springcloud-example-greenwich

SpringCloud Greenwich Version Example

![SpringCloud](https://img.shields.io/badge/Spring-SpringCloud-green.svg?style=plastic&logo=spring)

# 1 涉及环境说明

所有示例中涉及的环境，不限于Redis、MQ、Alibaba SpringCloud服务主键、三方服务注册中心，均需要自己搭建服务后，各示例工程才可运行。


# 2 项目说明

## 2.1 parent

全部示例项目模块的父模块，包含Maven父POM

## 2.2 eureka(Eureka注册中心Server)

- 启动说明
  - `dev`：开发环境，单节点注册中心
  - `peer1` && `peer2`：生产环境，2个节点高可用注册中心。注意，部署注册中心服务的2台主机，均需要设置host文件，映射2台主机的IP分别对应`peer1`和`peer2`。
