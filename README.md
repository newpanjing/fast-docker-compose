# fast-docker-compose

提供常用的软件/环境快速安装，基于：docker-compose.yml

## 包括以下软件快速安装

+ redis
+ jenkins
+ mongodb
+ nacos
+ nginx
+ mysql

## 密码

所有的软件采用国际通用密码：`123456`

如果要改成其他安全级别的，都可以在对于软件都`docker-compose.yml`中进行更改


## 安装

下面举例安装redis：

1. 切换到redis目录

```shell
cd redis
```

2. 使用docker-compose 构建服务

```shell
    docker-compose up
```

3. 启动服务

```shell
    docker-compose start
```

4. 重启服务

```shell
    docker-compose restart
```

5. 停止服务

```shell
    docker-compose stop
```

6. 查看日志

```shell
    docker-compose logs
```

7. 持续查看日志

```shell
    docker-compose logs -f
```

8. 查看运行中都镜像

```shell
    docker ps
```

+ 查看所有镜像，包括没有运行都
```shell
    docker ps -a
```


## 关于

本项目用于收集常用的一些软件的`docker-compose.yml`用于环境的快速安装

大家也可以在本项目提RP 贡献其他软件的`docker-compose.yml`