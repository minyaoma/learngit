
Windows���½� .gitignore �ļ����� ����������ļ�������
1. ����Ŀ��Ŀ¼���洴��gitignore.txt�ļ�
2. ������Ҫ�ų����ļ������浽gitignore.txt�ļ�
3. ����Ŀ��Ŀ¼���水סShift�����ʼ�Ȼ��ѡ���ڴ˴�������ڡ�
4. ִ�����ren gitignore.txt .gitignore


�����������޸ĵ���� git checkout -- file
�汾���˵����git reset HEAD~1


������Сд����

����1����������˹�����ĳ���ļ������ݣ���ֱ�Ӷ������������޸�ʱ��������git checkout -- file��
����2�����㲻�������˹�����ĳ���ļ������ݣ�����ӵ����ݴ���ʱ���붪���޸ģ�����������һ��������git reset HEAD <file>���ͻص��˳���1���ڶ���������1������
����3���Ѿ��ύ�˲����ʵ��޸ĵ��汾��ʱ����Ҫ���������ύ��ʹ�����git reset --hard HEAD^ �� git reset --hard commit_id������ǰ����û�����͵�Զ�̿⡣


Ҫ����һ��Զ�̿⣬ʹ������git remote add origin git@server-name:path/repo-name.git��
������ʹ������git push -u origin master��һ������master��֧���������ݣ�
�˺�ÿ�α����ύ��ֻҪ�б�Ҫ���Ϳ���ʹ������git push origin master���������޸ģ�

Creating a new branch is quick.
Git��������ʹ�÷�֧��
�鿴��֧��git branch
������֧��git branch <name>
�л���֧��git checkout <name>
����+�л���֧��git checkout -b <name>
�ϲ�ĳ��֧����ǰ��֧��git merge <name>
ɾ����֧��git branch -d <name>

Creating a new branch is quick AND simple.