1.  ssh -keygen -t rsa -C "邮箱地址" -->生成sshkey文件，在主机目录下.ssh文件下。
2.  ssh -T git@github.com -->检测github链接是否成功
3.  git remote add origin 'github地址' --> 添加远端仓库
4.  git add '文件' --> 将文件提交到暂存区
5.  git status --> 查看状态
6.  git commit -m "注释" --> 提交更改并添加注释
*** 
7.  git diff -->查看文件的具体更改
8.  git log --> 查看提交日志（详细）
9.  git log --pretty=online  --> 查看提交日志（简略）
10. git reset -hard HEAD^ --> 回到上一个版本
11. git reset -hard HEAD^^ --> 回到上上一个版本
12. git reset -hard HEAD~100 --> 回到前100个版本
13. git reflog --> 查看版本号
14. git reset -hard "版本号" --> 回到这个版本号的状态
***
15. cat '文件名' --> 查看文件
16. git checkout --"文件名" --> 丢弃工作区的更改
***
17. git branch --> 查看分支
18. git branch name --> 创建分支
19. git checkout name --> 切换分支
20. git checkout -b name --> 创建并切换分支
21. git merge name --> 合并某分支到当前分支
22. git branch -d name --> 删除某分支
*** 
23. git config --> git 配置
24. git config --global list --> 配置列表
25. git config --global user.name 'jiayanwen' --> 配置名字
26. git config --global user.email '71434890@qq.com' --> 配置邮箱
*** 
27. git stash --> 将当前的工作场景隐藏起来
28. git stash list
29. git stash apply --> 恢复隐藏的场景并不删除内容
30. git stash drop --> 删除内容
31. git stash pop --> 恢复隐藏的场景并删除内容
***
32. git remote -->要查看远程库的信息
33. git remote -v -->要查看远程库的详细信息
***
34. mkdir name --> 创建文件夹
35. cd name --> 进入文件夹
36. pwd --> 显示当前目录的路径
37. cd .. --> 后退一级
38. rm name --> 删除文件