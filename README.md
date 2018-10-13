# Todolist

## 用法

将 docker-compose.yml 文件 clone 到本地, 运行
```
docker-compose up
```
待下载完所有 images 并启动后, 访问 [localhost](http://localhost) 使用 todolist.

## 注意

app 没有提供单独的注册界面, 请在登录页面填入 username 和 password 之后, 点击 **REGISTER** 完成注册.

## 其他

也可以通过以下方式启动:
```
docker stack deploy -c docker-compose.yml todo
```

关闭:
```
docker stack rm todo
```

查看 service 的状态:
```
docker service ls
```
