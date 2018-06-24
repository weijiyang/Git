# Git
记录对git指令的练习操作

## master主干操作
* git init //初始化仓库
* git add . //把修改加入到stage中
* git clone xxx  //克隆代码到本地
* git commit -m "message"  //提交代码到远程库
* git push -u origin master //提交本地代码到远程库中
* git merge name //合并分支代码
* git push origin name //在master分支中进行分支代码的合并

## merge分支操作
* git branch //查看有哪些分支
* git branch -r/-a //查看远程分支or全部分支
* git branch name //新建一个name分支
* git checkout name //切换到name分支
* git checkout -b name //新建并切换到name分支
* git branch -d name //切换并删除name分支
* git merge master //把master分支上的代码merge到 该分支上
把master分支上的代码merge到 该分支上

## 团队合作开发
* git init //主干初始化项目
* git clone url  //初始化主干到本地
* git commit -m "" //主干提交代码
* git push -u origin master //主干代码push到远程服务器
* git branch -r/-a //主干查看远程分支or全部分支
* git checkout -b name //新建name分支
* git checkout -d name //删除name分支
* git checkout name //进入分支中
* git pull //分支中进行master 整体代码的更新
* git merge master //更新 name分支代码
* git stash //保存信息状态 切换分支前
* git stash pop //切换回原来的分支后 回复保存状态
* git commit -m "" //提交最新代码
* git checkout master//回到主分支
* git push origin name //将分支代码合并到主干

## 学习记录
* git branch name 创建分支
* git branch 查看当前目录所有分支
* git branch -a 查看远程分支（红色字）
* git checkout name 切换分支
* git checkout -b name 创建并切换到该分支
* git init 创建本地代码库
* git remote add <分支名称><仓库url> 创建服务器代码库
* git clone url 克隆服务器代码到本地
* git clone url directory 科通服务器代码到指定文件目录
* git status 查看缓存区的状态信息
* git stash 进行栈内保存
* git stash pop栈内状态恢复
* git stash list 栈内状态存储信息列表
* git stash apply stash@{1} 读取指定版本号的状态

* git branch --set-upstream-to=<远程主机名>/<远程分支名> 更改当前分支追踪的服务器分支
* git checkout -b <本地分支名>=<远程主机名>/<远程分支名> 更改当前分支追踪的服务器分支简写
* git branch <本地分支名>=<远程主机名>/<远程分支名> 更改当前分支追踪的服务器分支简写
* git branch -vv 查看全部分支的追踪关系
* git branch -d <本地分支>  删除本地分支
* git push origin --delete <远程分支>  删除远程分支
* git push origin :<远程分支>   删除远程分支（ 注意：push origin :second  有空格冒号前而后没有 ）

* git fetch <远程主机名> <远程分支名>：<本地分支名>  指定分支与本地分支同步
* git fetch <远程主机名>  同步代码库的全部分支
* git merge <本地分支> 同步本地代码分支
* git merge <远程主机> <远程分支> 同步远程到本地
* git reset <版本号>  回退到指定版本
* git reset HEAD^ 回退到上次提交
* git reset HEAD^^ 会退到上上次提交