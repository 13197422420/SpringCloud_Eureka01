# SpringCloud_Eureka01
软件服务工程实验一
一、	实验目的
（1）	学习分布式架构基础知识。
（2）	掌握SpringCloud微服务架构基础知识。
（3）	了解微服务架构中服务注册中心的基本作用。
（4）	掌握服务注册中心的创建和配置。
（5）	掌握微服务架构中服务的注册与发现方法。
（6）	掌握服务注册中心集群的创建和配置。
二、实验要求
（1）	SpringCloud版本必须为2022.0.0以上（即Kilburn），建议采用最新版本2022.0.2。
（2）	SpringBoot版本必须为3.0.0以上，建议采用最新版本3.0.5。
（3）	服务注册中心产品可选用Nacos、Eureka、Zookeeper。
（4）	实验代码请上传GitHub，并将链接提供到实验报告中。
（5）	请自行完成实验内容，切勿抄袭。
三、实验内容
（1）	使用IntelliJ IDEA新建Maven父工程，使用DependencyManagement在父工程中声明相应组件依赖（包括SpringCloud和SpringBoot），锁定版本号。
（2）	使用IntelliJ IDEA新建多个Maven子工程，分别实现多个服务调用者和服务消费者（使用不同端口号），服务的实现可自行确定，只需完成简单的服务逻辑即可。
（3）	使用IntelliJ IDEA新建Maven子工程，完成服务注册中心实例的创建与配置。
（4）	启动服务注册中心，展示服务注册中心管理后台。
（5）	将多个服务调用者和服务消费者（至少两组）注册到服务注册中心，并展示结果。
（6）	使用IntelliJ IDEA新建Maven子工程，再次新建服务注册中心实例，完成服务注册中心集群的创建和配置。
（7）	展示集群中服务注册中心的相互注册过程，展示微服务元数据的相互备份过程。
（8）	使用服务注册中心完成远程服务的发现与远程调用。
（9）	将工程上传GitHub个人账号并粘贴地址。
（10）	选做题：有能力的同学请完成两种服务注册中心产品的创建和配置（即上述1-8的过程），完成后予以大量加分。
