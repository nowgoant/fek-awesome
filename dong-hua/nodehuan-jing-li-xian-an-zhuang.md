#### 离线安装pm2 {#离线安装pm2}

先在一台能连网的Linux服务器上安装pm2

```
npm install pm2 -g

```

查询本机`npm`默认全局安装目录

```
npm config get prefix

```

如果显示`/usr/local/node`,则`npm`的默认全局安装目录是`/usr/local/node/lib/node_modules/`

在默认全局目录下找到`pm2`

```
cd
 /usr/
local
/node/lib/node_modules/

```

打包`pm2`

```
tar -cvzf pm2.tar.gz pm2

```

上传到内网Linux服务器的`npm`默认全局目录下，解压。

```
tar -xvzf pm2.tar.gz

```

重新编译

```
npm build pm2 -g

```

OK。大功告成，检验安装是否可用。

```
pm2 -v

```

如果显示版本号，就说明已经安装成功，可用使用`pm2`管理你的应用了

