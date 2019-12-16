# springcloud-example-greenwich
SpringCloud Greenwich Version Example

# 1 项目说明

## 1.1 parent

>所有示例项目模块的父模块，包含Maven父POM

## 1.2 eureka(Eureka注册中心Server)

- 启动说明
  - `dev`：开发环境，单节点注册中心
  - `peer1` && `peer2`：生产环境，2个节点高可用注册中心。注意，部署注册中心服务的2台主机，均需要设置host文件，映射2台主机的IP分别对应`peer1`和`peer2`。
