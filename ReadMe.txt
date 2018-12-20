
Windows下新建 .gitignore 文件出现 “必须键入文件名”：
1. 在项目根目录下面创建gitignore.txt文件
2. 把你需要排除的文件名保存到gitignore.txt文件
3. 在项目根目录下面按住Shift键并邮件然后选择“在此处打开命令窗口”
4. 执行命令：ren gitignore.txt .gitignore


丢弃工作区修改的命令： git checkout -- file
版本回退的命令：git reset --hard commit_id