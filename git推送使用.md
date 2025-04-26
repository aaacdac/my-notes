# git推送使用 #



## 推送修改过后的文件到git仓库  #

```
cd ./mt-notes

# 添加所有修改的文件到暂存区
git add .

# 提交更改到本地仓库（描述修改内容）
git commit -m "更新Mac端的笔记内容"  # 提交信息根据实际情况修改

# 推送本地提交到远程仓库（GitHub/GitLab）
git push origin main
```

#### **拉取最新内容（远程仓库 → 本地）**

在另一台电脑上操作前，先拉取远程仓库的最新内容：

bash

```
cd /path/to/my-notes
git pull origin main   # 拉取远程仓库的更新
```