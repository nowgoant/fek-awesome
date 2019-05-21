Command Line

* adduser nowgoant
* 加用户组 gpasswd -a nowgoant sudo （Adding user nowgoant to group sudo）
* 授权 sudo visudo
* 生产公钥和和私钥 ssh-keygen -t rsa -b 4096 -C "631359926@qq.com"

* 重启服务 sudo service ssh restart

* 启动ssh代理  eval "$\(ssh-agent -s\)"

* 加入到ssh代理 ssh-add ~/.ssh/id\_rsa

* 在服务器~/.ssh/下创建vim authorized\_keys 然后把本地生产的公钥拷贝到文件中

* 修改服务器的chmod 600 authorized\_keys 访问权限

* echo fs.inotify.max\_user\_watches=524288 \| sudo tee -a /etc/sysctl.conf && sudo sysctl -p

常用命令

```
# 查看文件大小
ls -lh logs/
# 查询大文件
find . -type f -size +800M  
# 如何查找Linux下的大目录
du -h --max-depth=1
```

系统命令

```
# centos 查看系统
rpm -q centos-release
cat /etc/redhat-release
```



