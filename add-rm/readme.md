# 增加删除
### 增加
- `git add file.xx` 将file.xx文件添加到缓存区
- `git add folder` 将folder目录添加到缓存区
- `git add .` 将当前目录下所有文件添加到缓存区
---
### 删除
- `git rm file.xx` 将file.xx从工作区删除，并把这次删除放入工作区
- `git rm --cached file.xx` 停止追踪file.xx文件，但该文件依然保留在工作区
- `git mv old.xx new.xx` 将old.xx文件改名为new.xx