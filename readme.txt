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
ssh-keygen -t rsa -C "598257867@qq.com"

	[git remote add origin https://github.com/Joeyskey/git.git #关联一个远程	库
	git remote add origin git@github.com:Joeyskey/git.git #关联一个远程库,速		度快,后期不需要输入用户名和密码
	git push -u origin master #第一次推送master分支的所有内容]

git push origin master	#本地提交后再提交到远程库
	git clone https://github.com/Joeyskey/BigData.git	#从远程库克隆
	git clone git@github.com:Joeyskey/BigData.git	#这样的形式也行,速度快



