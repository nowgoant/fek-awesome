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

2.文件版本操作

3.版本分支

| `$ git branch                # 列出本地分支` `$ git branch -a             # 列出本地所有分支`  `$ git checkout <branchName># 签出分支` `$ git branch <branchName># 基于当前分支创建新的分支` `$ git checkout -b <branchName># 基于当前分支创建新的分支并签出`  `$ git branch -m <branchName><newName># 不会覆盖已存在的同名分支` `$ git branch -M <branchName><newName># 会覆盖已存在的同名分支`  `$ git branch -d <newName># 如果分支未合并会删除失败` `$ git branch -D <newName># 强制删除分支`  `$ git branch -r -d origin/<branchName>#删除远程分支1` `$ git push origin :<branchName>#删除远程分支2`  `$ git branch -r                     # 列出所有远程库分支` `$ git remote prune origin           # 删除远程库不存在的分支` `$ git merge –no–ff <branchName># 快速合并分支` |
| :--- |


4.标签

| `$ git tag                               # 显示所有标签列表`  `$ git tag <tagName># 当前最后一次提交后的分支上创建标签` `$ git tag <tagName><branchName># 为特定分支最后一次提交后的状态创建标签` `$ git tag <tagName><version># 为历史版本提交创建标签`  `$ git checkout <tagName># 签出标签（快速查看基于某个标签下的断面，但不能提交）`  `$ git tag -d <tagName># 删除标签` |
| :--- |


5.远程Remote

| `$ ssh-keygen -t rsa -C "youremail@`[`example.com`](http://example.com/)`"#cat ~/.ssh/id_rsa.pub 上传公钥`  `$ git clone <URL>#克隆版本库`  `$ git remote add <origin><URL>#添加远程版本库origin` `$ git remote rm<origin>#删除远程版本库origin`  `$ git fetch <origin>#获取但不合并` `$ git pull = git pull <origin>#获取并合并到本地分支`  `$ git push <origin> master                        #推送远程库origin  第一次加上 -u` |
| :--- |


6.其他

| `$ git status    #当前状态` `$ git log       #历史日志` `/.gitignore     #忽略特殊文件，添加到版库中，也支持版本管理` `#简化命令行配置` `$ git config --global alias.st status       #输入git st = git status;   其他命令同理` |
| :--- |




