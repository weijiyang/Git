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
* git checkout -d name //切换并删除name分支
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