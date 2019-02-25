## Docker的文档：

* onShareAppMessage 钩子函数不能加 async 修饰



[https://yeasy.gitbooks.io/docker\_practice/cases/ci/travis.html](https://yeasy.gitbooks.io/docker_practice/cases/ci/travis.html)

运行docker不加sudo

```
# 第一步
sudo groupadd docker

# 第二步
sudo gpasswd -a vagrant docker

# 第三步
group docker

# 第四步
docker version

# 第五步
sudo service docker restart

# 第六步
exit

# 第七步
vagrant ssh
```



