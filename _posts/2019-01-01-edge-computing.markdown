---
layout: post
title:  "用于工业物联网的边缘计算平台研发"
date:   2019-01-01 21:03:36 +0530
categories: Java EdgexFoundry Openstack SpringBoot Vue
tag: "项目经历"
---
```
项目基于Edgex Foundry边缘计算开源框架进行了二次开发。
共分为三层架构：设备层、边缘层、云层。 
具体功能是实现了从设备层的传感器注册，通过消息队列（ActiveMQ/Kafka），将采集到的传感器的数据，
传递到智能网关设备中的各个Spring Boot微服务组件（如规则引擎、监控日志等），构成分布式网关网络。
同时边缘平台层还连接到云端层基于Openstack搭建的MySQL数据库，
实现了核心数据上云的存储，以及 HADOOP集群的大数据计算.
```
