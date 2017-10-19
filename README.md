# git操作和总结 #
## 1. 在GitHub项目创建一个项目  ##
![](https://i.imgur.com/jmLcZjW.png)
## 2. 创建后页面  ##
![](https://i.imgur.com/3ztSzvk.png)
## 3.指令创建文件夹
(1).mkdir git 创建git文件
(2).cd git   进入文件git
(3).git init 初始化文件
(4).git -v 查看git版本 ##
![](https://i.imgur.com/9gW4j7a.png)
## 4.创建README.md，操作下面指令
(1).echo "# git" >> README.md
(2).git init
(3).git add README.md
(4).git commit -m "first commit"
(5).git remote add origin https://github.com/chenlin1/git.git
(6).git push -u origin master ##
![](https://i.imgur.com/NuJlCvP.png)
## 在GitHub页面刷新会得到README.md如下图： ##
![](https://i.imgur.com/ofyOpmo.png)
## 5.在git文件夹创建index.js ##
![](https://i.imgur.com/JxDcYIK.png)
## 6.在git文件增加index.js(项目都可以) ##
![](https://i.imgur.com/X522fLE.png)
## 7.操作指令看README.md修改了没
(1). cat README.md 查看内容
(2).dir 查看git增加什么
(3).查看状态 git status ##
![](https://i.imgur.com/LKWkFtb.png)
## 8.提交项目到git
(1). git add . 提交文件
(2). git commit -m "first commit" 提交描述
(3). git push -u origin master 推送到master ##
![](https://i.imgur.com/juRlHxD.png)
## 9.在GitHub刷新页面看到结果如图 ##
![](https://i.imgur.com/I1eWbQC.png)
## 10.创建分支
(1). git checkout -b dev 创建dev分支
(2). git branch 查看多少分支
(3). git status 查看状态
(4). git diff 查看变更的内容 ##
![](https://i.imgur.com/VHwWVb3.png) 
在GitHub刷新可以看到创建dev分支