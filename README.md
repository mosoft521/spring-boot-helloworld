# spring-boot-helloworld
spring boot 1.5.22.RELEASE
spring-boot-helloworld
----
ref: http://jinnianshilongnian.iteye.com/blog/1997192
ref: http://blog.csdn.net/catoop/article/details/50588851
----
application.properties
----
# 服务端口
server.port=9090
----
java -jar spring-boot-helloworld-1.0-SNAPSHOT.jar --spring.config.location=~/application.properties
----
http://localhost:9090/user/1
http://10.10.135.100:9090/user/1