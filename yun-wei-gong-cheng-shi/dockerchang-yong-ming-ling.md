#Docker常用命令
## 查看已下载的镜像
```
docker image ls
```
## 查看当前正在运行的容器
```
docker ps
```

## 查看所有容器
```
docker ps -a
```
## 使用帮助命令
```
docker --help
docker container --help
docker container ls --help
docker run --help
```

## 拉取并运行 nginx 网页服务器，并命名为 webserver
```
docker run --detach --publish 80:80 --name webserver nginx
```