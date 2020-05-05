# git-learning
git config --global user.name "你注册GitHub账号的名字"

git config --global user.email "你注册GitHub账号用的邮箱.com"
cd ~/.ssh
ssh-keygen -t rsa -C "你注册GitHub账号时用的邮箱"
git init
git add .
git commit -m "你的说明注释"
git remote add origin 你的仓库地址
git featch 你的仓库地址
git pull --rebase origin master
git push -u origin master
