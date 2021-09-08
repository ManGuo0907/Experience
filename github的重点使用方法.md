+ #### 第一步：建立git仓库，cd（切换）到自己的本地项目根目录下，执行git命令。

```
git init
```

+ #### 第二步：将项目的所有文件添加到仓库中

```
git add .
```

+ #### 第三步：将add的文件commit到仓库

```
git commit -m"注释语句"
```

（第二步与第三步都是提交到本地仓库中）

+ #### 第四步：去GitHub上创建自己的Repository，创建后的页面如下图所示：

![](https://pic1.zhimg.com/v2-a4e249c5e85f6f5ca6c56fc916c150ac_r.jpg)

+ #### 第五步：将本地的仓库关联到github上---把上一步复制的地址放在下面

```
git remote add origin git@github.com:***/test.git
```

+ #### 第六步：上传GitHub之前，要先pull一下，执行如下命令：

```
git pull origin master
```

+ #### 第七步：上传代码到github远程仓库中

```
git push -u origin master
```

(第五，六，七步都是上传到远程仓库中。)