git
git config --global user.name "Joeyskey"
git config --global user.email "598257867@qq.com"
#��һ����һ��ר�ŷ��ļ����ļ���,����ȡ��Ϊgit
git init
git add ***(�ļ���)
git commit -m "�޸�˵��"
git status
git diff
git log --pretty=oneline	#�����Ǹ�--pretty=oneline���Բ���
git reset --hard head^
git reset --hard ******
git reflog
git diff head -- ***	#�鿴�汾������ļ��͹��������ļ�������
git checkout -- ***	#���ļ��ص����һ��git commit��git add��״̬
git reset head ***	#���ݴ������ļ��˻ص�������
ssh-keygen -t rsa -C "598257867@qq.com"

	[git remote add origin https://github.com/Joeyskey/git.git #����һ��Զ��	��
	git remote add origin git@github.com:Joeyskey/git.git #����һ��Զ�̿�,��		�ȿ�,���ڲ���Ҫ�����û���������
	git push -u origin master #��һ������master��֧����������]

git push origin master	#�����ύ�����ύ��Զ�̿�
	git clone https://github.com/Joeyskey/BigData.git	#��Զ�̿��¡
	git clone git@github.com:Joeyskey/BigData.git	#��������ʽҲ��,�ٶȿ�



