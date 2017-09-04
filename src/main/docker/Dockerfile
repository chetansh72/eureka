FROM java
VOLUME /tmp
WORKDIR /home/msa/workspace/eureka/target
ADD eureka-0.0.1-SNAPSHOT.jar /eureka.jar
EXPOSE 8761
ENTRYPOINT ["java","-jar","/eureka.jar"] 

