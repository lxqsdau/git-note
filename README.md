# git 笔记
* 新建本地分支，并同步远程分支
> git checkout -b dev origin/dev

* 合并或提交  Please enter a commit message to explain why this merge is necessary.
> 按esc，输入:wq，按回车键退出

## tag 发版本号
> * 提交后graym
> * git tag graym/0.0.1
> * git push origin graym/0.0.1

## git 流程
> * git clone
> * git checkout -b dev origin/dev
> * ga .
> * gcmsg ""
> * gl
> * gp

## 合并分支
> * git checkout online
> * gl
> * git merge master
> * gp

## 删除远程分支
git push origin --delete future