## Pro Admin 后台管理系统服务端

### 项目介绍
Pro Admin 后台管理系统服务端，使用 Golang Gin 开发框架

### DockerCompose 容器开发环境
启动环境
```
docker compose up -d
```
关闭环境
```
docker compose down
```


### Docker 容器开发环境
在项目目录执行如下命令
```
docker run -itd \
    --name progo \
    -p 8686:2020 \
    -v $(pwd):/app \
    -w /app \
    golang:1.22
```
