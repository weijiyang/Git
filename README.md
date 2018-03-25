# Git
记录对git指令的练习操作

## master主干操作
* git init //初始化仓库
* git add . //把修改加入到stage中
* git clone xxx  //克隆代码到本地
* git commit -m "message"  //提交代码到远程库
* git push -u origin master //提交本地代码到远程库中

## merge分支操作
* git branch //查看有哪些分支
* git branch -r/-a //查看远程分支or全部分支
* git branch name //新建一个name分支
* git checkout name //切换到name分支
* git checkout -b name //新建并切换到name分支
* git checkout -d name //切换并删除name分支
* git merge master //把master分支上的代码merge到 该分支上