合并上游变更

```

# 1. 拉取上游最新代码
git fetch upstream

# 2. 切换到你的主分支（当前已是 master）
git checkout master

# 3. 合并上游 master（二选一）

# 方式 A：merge（保留合并记录，更安全）
git merge upstream/master

# 方式 B：rebase（历史更线性，适合个人 fork）
# git rebase upstream/master

# 4. 推送到你的 fork
git push origin master

```