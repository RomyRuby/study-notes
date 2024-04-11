## nrm

镜像管理工具，用来快速切换各种国内镜像。

#### 1. 安装

```
npm install -g nrm
```



#### 2. 查看镜像列表

```
nrm ls
```

结果：

![image-20240410104631365](../../Pictures/前端学习笔记图片/image-20240410104631365.png)****

#### 3. 选择镜像

```
nrm use npm/yarn/tencent/cnpm/taobao/npmMirror
```



#### 4. 查看当前源

```
nrm current
```



#### 5. 当前源测速

```
nrm test
```



#### 6. npm 设置源方法

```
npm config set registry https://registry.npmmirror.com
```



#### 7. 使用淘宝镜像命令

```
npm install -g cnpm --registry=https://registry.npmmirror.com
```



#### 8. Mac m1芯片安装失败问题

```
npm uninstall -g nrm
npm i -g @adams549659584/nrm
```

