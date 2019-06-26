FROM centos-jdk8:211
VOLUME /yly/dubbo-admin
ADD /target/dubbo-admin-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]