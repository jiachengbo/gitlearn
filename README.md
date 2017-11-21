# git学习笔记

***
## 一。本地已经有仓库，连接远端仓库
1.  本地仓库的我建立 git init ，存放自己要上传到GitHub的文件
2.  在github上建立仓库，复制仓库的链接
3.  在本地仓库的目录下，打开git命令行，运行 git remote add origin "你的GitHub地址"
4.  运行git push -u origin master 将本地仓库的内容推送到远端仓库（请确保本地仓库里面已经有内容）
