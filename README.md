# 发布npm模块

首先，进行登录，若当前仓库路径即为所需发布模块的目标路径，则直接执行：

```text
npm adduser
```

然后根据命令行提示输入用户名和密码。若需要发布到指定仓库地址，则执行如下命令：

```text
npm adduser --registry yourregistrypath
```

登录成功之后，即可执行一下命令进行发布

```text
npm publish
```



