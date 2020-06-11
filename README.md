# lsqaure.github.io

静态页面...顺便学习下  git 命令







- 1.先建立  `lsqaure.github.io `  作为仓库名字。

- 2.本地克隆

本地创建文件夹，用于存放远程仓库，打开所创建的文件夹，右键选择`git bash here`，表示在当前目录打开`git bash`程序，然后执行如下命令，将刚才创建的仓库克隆到本地：

```
git clone https://github.com/AmazingChen/lsqaure.github.io.git
```



介绍几个常用命令：

```
git add . //添加文件
git commit -m "commit-messages" //提交本地仓库
git push origin master //提交远程仓库
git pull //拉取远程文件，与以下命令类似
git branch temp //创建本地分支
git fetch origin master:temp
git merge master
```

