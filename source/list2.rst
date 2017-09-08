将 Sphnix 生成的文档和配置 push 到远程 github
=============================================
先在GitHub创建一个仓库名字
打开 git Bash（安装过git就有，在开始-所有程序里就能找到），进入刚刚创建的工程中，依次命令
git init 

git add .

git commit -m "sphinx start" 

git remote add origin https://github.com/[yourusename]/[yourrepository].git 

git push origin master

注意：[yourusename]/[yourrepository] 换成你的 github 名和仓库名。