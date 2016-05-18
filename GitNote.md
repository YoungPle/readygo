#1.创建版本库
##git init

#2.添加文件到暂存区
##git add filename

#3.将工作区代码提交到版本库
##git commit -m "commit message"

#4.查看当前状态
##git status

#5.查看文件修改
##git diff filename
##git diff HEAD --filename

#6.查看版本修改记录
##git log
##git log --pretty=oneline

#7.回退版本 
##git reset --hard HEAD^ #回退到上一个版本 HEAD表示当前版本
##git reset --hard commit-id # 回退到指定的commit-id

#8.查看历史命令记录
##git reflog

#9.工作区和暂存区
##9.1 工作区：就是本地目录
##9.2 暂存区：通过git add就是将文件放入暂存区
##9.3 通过git commit就是将暂存区的文件提交到当前分支

#10.撤销修改
##10.1 git checkout --filename #撤销工作区的修改,必须包含"--"，否则就是创建一个新的分支了
##10.2 git reset HEAD filename #撤销暂存区的修改,即恢复到上一个版本

#11.删除文件
##在本地执行 rm filename
##git rm filename

#12.创建远程仓库
##12.1 创建SSH Key
		ssh-keygen -t rsa -C "93716292@qq.com"
##12.2 在github个人账号设置里添加SSH Key(id_rsa.pub)

#13.添加远程仓库
##13.1 在github上创建一个repository
##13.2 将本地仓库与github上的仓库关联
	git remote add origin git@github.com:YoungPle/readygo.git
##13.3将本地仓库推送到github
	git push -u origin master #-u表示将本地的master分支和github上的mster关联、后面的修改推送不需要改选项
	
#14.克隆github上的版本库到本地
##git clone git@github.com:YoungPle/readygo.git



