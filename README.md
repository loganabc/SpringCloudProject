# SpringCloudProject
右键点击EurekaserverApplication8761，选择Edit‘EurekaserverApplica...’...
然后在Configuration中的Environment中找到Program arguments:
然后填入如下参数
--spring.profiles.active=eureka8762

EurekaserverApplication8762上面类似操作
--spring.profiles.active=eureka8761

即可配置Eureka注册中心启动的配置文件
 两个一起运行即可搭建Eureka注册中心集群

