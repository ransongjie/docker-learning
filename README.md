# docker-compose安装mysql5.7.26
```shell
# 启动
sudo docker-compose -f mysql.yaml up -d
# 检查
sudo docker logs -f mysql7
```

# docker-compose安装redis6.0.16
```shell
# 启动
sudo docker-compose -f redis.yaml up -d
# 检查
sudo docker logs -f redis6
```