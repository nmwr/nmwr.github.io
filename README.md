# nmwr.github.io
个人网站

新建一个仓库，把仓库名命名为你的  用户名 + github.io
在新建一个文件，后缀名要是.html,静态

git config --global user.name "你的用户名"
git config --global user.email "你的邮箱"
git config user.name 查看配置后的用户名
git config user.email 查看配置后的邮箱号

cd /你要进入的盘
mkdir nmwr  创建nmwr文件夹/文件
cd nmwr/ 进入nmwr文件夹/文件
git clone https://github.com/nmwr/nmwr.github.io.git 将nmwr上的nmwr.github.io仓库克隆到本地
vim/vi nmwr.txt 建立一个txt文本文件
git init 初始化仓库
git remote add origin https://github.com/nmwr/nmwr.github.io.git  添加远程仓库
git pull --rebase origin master 获取远程库与本地仓库同步（远程仓库不为空需要这一步）
git nmwr.txt  将工作区创建的nmwr.txt添加到暂存区
git commit -m “匿名温柔”  将暂存区的内容提交到仓库区，-m是备注信息
git push origin master
