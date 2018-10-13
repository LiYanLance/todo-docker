# Todolist

## 用法

将 docker-compose.yml 文件 clone 到本地, 运行
```
docker stack deploy -c docker-compose.yml todo
```

当所有 service 启动后, 访问 [localhost](http://localhost) 即可进入 todolist.

关闭方法:
```
docker stack rm todo
```

BTW, 查看 service 的启动情况:
```
docker service ls
```

## 注意
app 没有提供单独的注册界面, 请在登录页面填入 username 和 password 之后, 点击 **REGISTER** 完成注册.


