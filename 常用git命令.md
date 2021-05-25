## 常用git命令

1. git clone git@192.168.1.124:Terminal/4G_Common.git

2. 有几个^就会打几个patch，从最近一次打起 

   git format-patch HEAD^
   
3.  git push origin --tags
	推送tag到远程仓库
	
4. 解决二进制冲突

   git checkout FILE --ours [ --theirs ]

   –ours 表示检出当前分支,即保存当前分支的改动,丢弃另外分支的改动.
   –theirs 表示检出另外分支, 即保存另外分支的改动,丢弃当前分支的改动.

