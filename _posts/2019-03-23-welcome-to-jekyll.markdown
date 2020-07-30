---
layout: post
title:  "用于工业物联网的边缘计算平台研发"
date:   2019-01-01 21:03:36 +0530
categories: Java EdgexFoundry Openstack SpringBoot Vue
---
项目基于Edgex Foundry边缘计算开源框架进行了二次开发。共分为三层架构：设备层、边缘层、云层。 具体功能是实现了从设备层的传感器注册，通过消息队列（ActiveMQ/Kafka），将采集到的传感器的数 据，传递到智能网关设备中的各个Spring Boot微服务组件（如规则引擎、监控日志等），构成分布式网关 网络。同时边缘平台层还连接到云端层基于Openstack搭建的MySQL数据库，实现了核心数据上云的存 储，以及 HADOOP集群的大数据计算

```javascript
const Razorpay = require('razorpay');

let rzp = Razorpay({
	key_id: 'KEY_ID',
	secret: 'name'
});

// capture request
rzp.capture(payment_id, cost)
	.then(function (data) {
		return 2;
	})
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
