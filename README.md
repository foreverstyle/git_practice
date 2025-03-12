<!--
 * @Author: foreverstyle
 * @Date: 2025-03-12 21:30:24
 * @LastEditTime: 2025-03-12 22:15:46
 * @Description: 练习git的使用，参考菜鸟教程
 * @FilePath: \git_practice\git_practice\README.md
-->

# git_practice

Shift + Alt + F 可以实现代码对齐

Ctrl + Win + I 生成注释

在 bash 环境下使用Ctrl + Shift + V 粘贴 使用 Ctrl + Shift + C复制

创建新的分支 "git config user.name && git config user.email"

git add .

git commit -m "Add new feature"

在推送本地更改之前，最好从远程仓库拉取最新的更改，以避免冲突：
git pull origin main

git push origin new-feature

合并更改
git checkout main
git pull origin main
git merge new-feature
