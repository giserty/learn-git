# 推送方法
## 首次推送
git init
git add .
git commit -u "提交信息"
git remote add git@github.com:giserty/仓库名.git
git push -u origin master

## 之后推送
git add .
git commit -u "提交信息"
git pull --rebase origin master
git push -u origin master
