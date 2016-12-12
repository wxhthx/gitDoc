# linux使用su切换用户提示 Authentication failure的解决办法
## 这个问题产生的原因是由于ubtun系统默认是没有激活root用户的，需要我们手工进行操作

在终端中输入如下命令：

```Bash
sudo passwd
```

Enter new UNIX password：这个是root的密码

Retype new UNIX password：重复root的密码
然后会提示成功的信息。

在说明一点，使用su和sudo是有区别的，使用su切换用户需要输入所切换到的用户的密码，而使用sudo则是当前用户的密码。
