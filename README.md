# git-review

## 工作区 (Working Directory)

- `git add`
对工作区修改, 暂存区目录树被更新

## 暂存区(Stage Area)

- git commit

暂存区的目录树写入版本库中
master branch 会做相应的更新
master指向的目录树就是提交时的暂存区的目录树

## 版本库(Repository)

- Concepts
- git reset HEAD 暂存区的目录树写入到版本库中
- git rm --cached <file> 从暂存区删除文件工作区没有改变


## Relationship between W.S.R.

Working Directory -> Stage Area -> Repository -> Remote Repository

## Branch

- git checkout -b <branchname> 创建并且切换到该分枝
- git branch -r 查看远程分枝
- git branch -a 查看所有本地和远程分枝
- git branch -d <branch> 删除本地分枝
- git push origin --delete <branchname> 删除远程分枝

## merge

- git merge <branchname> 合并
