FROM ewolff/docker-java
#ADD /var/lib/jenkins/workspace/Eureka/Lego_ms_eureka-Build/microservice-demo/microservice-demo-eureka-server/target/microservice-demo-eureka-server-0.0.1-SNAPSHOT.jar .
ADD ~/workspace/Eureka/../../../target/microservice-demo-eureka-server-0.0.1-SNAPSHOT.jar .
CMD /usr/bin/java -Xmx400m -Xms400m -jar microservice-demo-eureka-server-0.0.1-SNAPSHOT.jar
EXPOSE 8761
