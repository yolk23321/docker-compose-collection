# docker-compose-collection
![](docker-dashboard.png)

## Usage
```bash
# install kafka
# -d 表示分离模式，会使容器在后台运行，而不是将容器的输出直接显示在终端中
docker-compose -f mq/docker-compose.yaml up -d

# install es、logstash、kibana
docker-compose -f elk/docker-compose.yaml up -d

# 等等
```
> 更新配置后，同样执行上面的命令即可生效