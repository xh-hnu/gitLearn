## Android studio git 的基本操作
1.	创建本地仓库 <br>
git init <br>
git add * <br>
git commit –m ‘first commit’<br>
2.	创建远程仓库<br>
3.	连接远程仓库<br>
git remote add origin 远程仓库地址<br>
git remote rm origin<br>
4.	将本地分支推送到远程<br>
git push –set-upstream origin 分支名<br>
git push origin 本地分支名：远程分支名<br>
5.	将远程分支拉到本地<br>
git checkout –b 本地分支名 origin/远程分支名<br>
6.	切换分支<br>
git checkout 分支名<br>
git branch<br>
7.	提交到远程仓库<br>
git push –u origin master<br>
git push –u origin 分支名<br>
