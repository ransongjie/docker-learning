# docker-compose安装mysql5.7.26
```shell
# 启动
mkdir -p mysql6.7.26/data mkdir mysql6.7.26/sql
sudo docker-compose -f mysql.yaml up -d
# 检查
sudo docker logs -f mysql7
```

# docker-compose安装redis6.0.16
```shell
mkdir -p redis6.0.16/data
# 启动
sudo docker-compose -f redis.yaml up -d
# 检查
sudo docker logs -f redis6
```

# docker-compose安装mongo:5.0
```shell
mkdir -p mongo5.0/db mongo5.0/log mongo5.0/cfg
# 启动
sudo docker-compose -f mongo.yaml up -d
# 验证
sudo docker logs -f mongo5
```

# docker-compose安装minio22
```shell
mkdir -p minio22/data minio22/config
# 启动
sudo docker-compose -f minio.yaml up -d
# 验证
sudo docker logs -f minio22
```