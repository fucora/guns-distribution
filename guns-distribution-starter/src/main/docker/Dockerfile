FROM registry.cn-shanghai.aliyuncs.com/c7n/javabase:0.8.0
MAINTAINER FuFei
WORKDIR /runtime
COPY guns-distribution-starter.jar app.jar
ENTRYPOINT ["tini","--","java","-Djava.security.egd=file:/dev/./urandom","-jar","/runtime/app.jar"]