查看git版本
git --version

设定 名字 邮件
git config --global user.name "zoooi"
git config --global user.email "johnooi9918@gmail.com"

初始化
git init

档案状态
git status

追踪档案 U --> A
git add
U = Untracked
A = Added

git commit -m "message"

查看 提交历史
git log
q == quit
git log --oneline

差异
git diff
git diff 1c6680d -- Price.md
