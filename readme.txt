git
git config --global user.name "Joeyskey"
git config --global user.email "598257867@qq.com"
#这一步建一个专门放文件的文件夹,比如取名为git
git init
git add ***(文件名)
git commit -m "修改说明"
git status
git diff
git log --pretty=oneline	#后面那个--pretty=oneline可以不加
git reset --hard head^
git reset --hard ******
git reflog
git diff head -- ***	#查看版本库里的文件和工作区的文件的区别
git checkout -- ***	#让文件回到最近一次git commit或git add的状态
git reset head ***	#把暂存区的文件退回到工作区
