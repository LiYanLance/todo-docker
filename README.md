# Todolist

## 用法

将 docker-compose.yml 文件 clone 到本地后, 执行
```
docker stack deploy -c docker-compose.yml todo
```
等待 docker 下载所有的 image.  

当所有 service 启动后, 访问 [localhost](http://localhost) 即可进入 todolist.

使用
```
docker stack rm todo
```
关闭.

BTW, 可以使用 
```
docker service ls
```
查看 service 的启动情况

## 注意
app 没有提供单独的注册界面, 请在登录页面填入 username 和 password 之后, 点击 **REGISTER** 完成注册.


