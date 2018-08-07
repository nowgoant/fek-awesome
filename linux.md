Command Line

* adduser nowgoant
* 加用户组 gpasswd -a nowgoant sudo （Adding user nowgoant to group sudo）
* 授权 sudo visudo
* 生产公钥和和私钥 ssh-keygen -t rsa -b 4096 -C "631359926@qq.com"

* 重启服务 service ssh restart

* 启动ssh代理  eval "$\(ssh-agent -s\)"

* 加入到ssh代理 ssh-add ~/.ssh/id\_rsa

* 在服务器~/.ssh/下创建authorized\_keys 然后把本地生产的公钥拷贝到文件中

* 修改服务器的chmod 600 authorized\_keys 访问权限


