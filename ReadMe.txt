
Windows下新建 .gitignore 文件出现 “必须键入文件名”：
1. 在项目根目录下面创建gitignore.txt文件
2. 把你需要排除的文件名保存到gitignore.txt文件
3. 在项目根目录下面按住Shift键并邮件然后选择“在此处打开命令窗口”
4. 执行命令：ren gitignore.txt .gitignore


丢弃工作区修改的命令： git checkout -- file
版本回退的命令：git reset HEAD~1


擦，大小写敏感

场景1：当你改乱了工作区某个文件的内容，想直接丢弃工作区的修改时，用命令git checkout -- file。
场景2：当你不但改乱了工作区某个文件的内容，还添加到了暂存区时，想丢弃修改，分两步，第一步用命令git reset HEAD <file>，就回到了场景1，第二步按场景1操作。
场景3：已经提交了不合适的修改到版本库时，想要撤销本次提交，使用命令：git reset --hard HEAD^ 或 git reset --hard commit_id，不过前提是没有推送到远程库。


要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
关联后，使用命令git push -u origin master第一次推送master分支的所有内容；
此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；

Creating a new branch is quick.
Git鼓励大量使用分支：
查看分支：git branch
创建分支：git branch <name>
切换分支：git checkout <name>
创建+切换分支：git checkout -b <name>
合并某分支到当前分支：git merge <name>
删除分支：git branch -d <name>

Creating a new branch is quick AND simple.