#geeksword-study
中心仓库 fork--->> A、B、C的远程仓库  clone--->> A、B、C本地仓库

A完成操作 （push） --->> A的远程仓库 （push request等待同意）--->> 中心仓库

 B 可以直接拉取 A远程仓库的代码或者中心仓库的代码来完成工作  
 给B添加A的远程仓库
$ git remote add A  https://github.com/A/datura-lj/git-fork-demo.git 
$ pull A master

向github提交内容：
1、建立一个远程仓库 （文件夹init或者在网页上操作）
2、通过http或ssh连接到远程
3、添加文件 git add -file 
4、提交并附上描述 git commit -m "discribion"
5、推送到远程仓库 git push origin master
6、添加一个远程仓库并命名为 zls: git remote add zls https://github.com/zls/datura-lj/git-fork-demo.git 
7、查看所连接的远程 git remote -v
8、拉取并合并中心仓库最新代码 git pull upstream xwy 推送到中心仓库：git push upstream xwy
