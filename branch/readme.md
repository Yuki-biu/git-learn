# 分支相关
 
## 列出分支
- `git branch` 列出本地分支
- `git branch -r` 列出远程分支
- `git branch -a` 列出本地 & 远程分支
---
## 新建分支
- `git branch dev` 新建dev分支 但停留在当前分支
- `git checkout -b dev` 新建dev分支 并切换到dev分支
- `git checkout -b dev origin/dev` 基于远程仓库的dev分支新建dev分支
---
## 切换分支
- `git checkout dev` 切换到dev分支
- `git checkout -` 切换到上一个分支
---
## 删除分支
- `git branch -d dev` 删除dev分支
- `git branch -D dev` 强制删除dev分支
- `git push origin --delete dev` 删除远程dev分支
---
## 分支合并
- `git merge dev` 将dev分支合并到当前分支