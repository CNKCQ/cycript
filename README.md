# cycript
See: http://www.cycript.org

```shell
scp -P 22 cycript.cy root@192.168.0.100:/usr/lib/cycript0.9/cycript.cy
```

* 查找 pid

```shell
frida-ps -Ua
```

* cycript 注入对应进程

```shell
cycript -p 75043
```

* 导入自定义函数块

```shell
@import cycript
```
* 获取 appId

```shell
appId
```

* 获取 Key window

```shell
keyWin()
```
* 调用带有参数的函数

```shell
vcSubviews(#0x10b91d800)
```
