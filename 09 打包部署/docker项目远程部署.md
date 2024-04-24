## mac连接远程发布docker项目步骤

```
ssh root@47.96.105.175 -p 22 //连接进入服务器
ll //查看文件列表
cd 进入对应文件夹
git pull //git拉取部署好docker发布的项目代码
gitlog //查看git日志，复制需要发布的版本号
make commit_id=<版本号> //发布
docker logs -f <发布项目名> //查看有没有报错

```

