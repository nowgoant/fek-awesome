```
# 是否安装mysql
rpm  -qa | grep  mysql

# nodeps表示强制删除
rpm -e  –nodeps mysql-5.0.77-4.el5_4.2

# 查看文件安装路径
whereis mysql

# 查询运行文件所在路径(文件夹地址) 
which mysql

# linux下执行mysql的sql文件 
mysql -uroot -proot
# 进入到mysql
# 然后执行source /var/ftp/pub/sogoodsoft.sql;

MySQL重启
使用 service 启动：service mysqld restart
```



