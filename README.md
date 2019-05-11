# itoken
微服务架构实战


#### 基于Docker安装Nexus
```text
# pull
docker pull sonatype/nexus3

# run
docker run -d -p 8081:8081 --name nexus sonatype/nexus3
```

#### 服务IP汇总
```text
- config: 172.28.7.47:8888
- admin: 172.28.7.32:8084
- zipkin: 172.28.32
- eureka: 172.28.7.46:8761
- nexus: 172.28.7.36:8081

```