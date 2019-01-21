# first-springboot

1：采用Spring Initializr搭建，Spring Initializr是官方提供的一种快捷搭建Spring Boot应用的方式。网址: https://start.spring.io/ 
        
2 Application类放在最外侧,即包含所有子包，因为spring-boot会自动加载启动类所在包下及其子包下的所有组件.

3 定义用户模型，包括属性：用户ID和名称

4 客户端发送POST请求，创建用户（Web MVC）

5 客户端发送GET请求，获取所有用户（Web Flux）
