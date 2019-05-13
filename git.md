git安装后设置用户和邮箱

```
$ git config --globaluser.name"Your erp"
$ git config --global user.email "email@jd.com"
```

记住密码

```
$ git config --global credential.helper store
```

可使用TortoiseGit或其他图形化客户端

## 常用命令 {#id-配置git-常用命令}

1.配置Git

`# 检查已有配置信息`

  


`$ git config --list`

  


`# 配置信息设置`

  


`$ git config --global `

[`user.name`](http://user.name/)

`"Your Name"`

  


`$ git config --global user.email `

`"email@`

[`example.com`](http://example.com/)

`"`

  


`$ git config --global color.ui `

`"always"`

2.文件版本操作

3.版本分支

4.标签

5.远程Remote

6.其他



