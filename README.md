微服务注册中心：

微服务注册：
在application.yml中配置（若是集群注册中心，需要填写多个地址，以逗号分隔）：
eureka.client.serviceUrl.defaultZone=http://${host}:${port}/eureka(具体服务注册地址和端口视部署环境而定)
启动命令java -jar target/eureka-server-center.jar --spring.profiles.active=dev1

