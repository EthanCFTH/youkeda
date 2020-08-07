##绑定本地仓库到GitHub

git init
    将一个文件夹初始化为一个git仓库
    如果初始化错误，需要删除被初始化文件夹下面的 .git文件夹（这是一个隐藏文件），再重新进行初始化

git remote -v
    查看当前git仓库绑定的远程仓库
    刚刚初始化的仓库一般来说是没有绑定远程仓库的，而从线上clone下来的仓库是必然有远程绑定的
    若使用该命令时，显示是空白的，即是无绑定

git remote add origin 仓库地址
    绑定远程仓库

git remote remove origin
    移除绑定


