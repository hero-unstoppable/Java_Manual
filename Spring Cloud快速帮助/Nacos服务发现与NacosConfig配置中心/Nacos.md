# Nacos是什么？

​		Nacos是易于使用的动态服务发现，配置和服务管理平台，用于构建云本机应用程序，由阿里巴巴开源

# Nacos能做什么？

动态配置服务 

​			动态配置服务允许您以集中，外部化和动态的方式管理所有环境中的配置。动态配置可以帮助您在		

​			更新配置时重新部署应用程序和服务。您可以轻松实现无状态服务并实现按需扩展 

服务发现和管理

​			动态服务发现是以服务为中心（例如微服务或云原生）体系结构的关键。Nacos支持基于DNS和基	

​			于RPC（Dubbo，gRPC）的服务发现，并提供实时服务运行状况检查，以防止将路由请求发送到不

​			健康的主机或服务实例。使用Nacos，您还可以轻松地为您的服务实施断路器。 

动态DNS服务 

​			通过支持加权路由，动态DNS服务可帮助您在数据中心的生产环境中实施中间层负载平衡，更灵活

​			的路由，流量控制和DNS解析服务。动态DNS服务还使您可以更轻松地实施基于DNS的服务发现，	

​			从而最大限度地降低与特定于供应商的服务发现API耦合的风险。 

# 如何安装Nacos？

​		我们首先需要安装Nacos，我们可以去github上，https://github.com/alibaba/nacos，下载之后接压，然后，放到服务器上，我们进入到他的bin目录下，然后使用

​	sh startup.sh -m standalone

​	，这样就能启动我们的Nacos了，

​	![](img\Nacos安装.png)

这个时候不要关闭窗口，我们直接访问http://你的ip:8848/nacos/index.html

就能进入下面的界面了

![](img\登录界面.png)

默认用户名和密码都是     nacos

注意：如果输入密码还是不对，检查你的jdk，如果jdk是openjdk可能会出现问题将它换了就好了

然后就能进入到控制台了

![](img\控制台.png)

