## Android studio git 的基本操作
1.	创建本地仓库
git init 
git add *
git commit –m ‘first commit’
2.	创建远程仓库
3.	连接远程仓库
git remote add origin 远程仓库地址
git remote rm origin
4.	将本地分支推送到远程
git push –set-upstream origin 分支名
git push origin 本地分支名：远程分支名
5.	将远程分支拉到本地
git checkout –b 本地分支名 origin/远程分支名
6.	切换分支
git checkout 分支名
git branch
7.	提交到远程仓库
git push –u origin master
git push –u origin 分支名
