#1.�����汾��
##git init

#2.����ļ����ݴ���
##git add filename

#3.�������������ύ���汾��
##git commit -m "commit message"

#4.�鿴��ǰ״̬
##git status

#5.�鿴�ļ��޸�
##git diff filename
##git diff HEAD --filename

#6.�鿴�汾�޸ļ�¼
##git log
##git log --pretty=oneline

#7.���˰汾 
##git reset --hard HEAD^ #���˵���һ���汾 HEAD��ʾ��ǰ�汾
##git reset --hard commit-id # ���˵�ָ����commit-id

#8.�鿴��ʷ�����¼
##git reflog

#9.���������ݴ���
##9.1 �����������Ǳ���Ŀ¼
##9.2 �ݴ�����ͨ��git add���ǽ��ļ������ݴ���
##9.3 ͨ��git commit���ǽ��ݴ������ļ��ύ����ǰ��֧

#10.�����޸�
##10.1 git checkout --filename #�������������޸�,�������"--"��������Ǵ���һ���µķ�֧��
##10.2 git reset HEAD filename #�����ݴ������޸�,���ָ�����һ���汾

#11.ɾ���ļ�
##�ڱ���ִ�� rm filename
##git rm filename

#12.����Զ�ֿ̲�
##12.1 ����SSH Key
		ssh-keygen -t rsa -C "93716292@qq.com"
##12.2 ��github�����˺����������SSH Key(id_rsa.pub)

#13.���Զ�ֿ̲�
##13.1 ��github�ϴ���һ��repository
##13.2 �����زֿ���github�ϵĲֿ����
	git remote add origin git@github.com:YoungPle/readygo.git
##13.3�����زֿ����͵�github
	git push -u origin master #-u��ʾ�����ص�master��֧��github�ϵ�mster������������޸����Ͳ���Ҫ��ѡ��
	
#14.��¡github�ϵİ汾�⵽����
##git clone git@github.com:YoungPle/readygo.git



