# Git-learn
1.转到d盘：cd d:
2.转到d盘git： cd git
3.创建文件： mkdir learn
4》转到learn： cd learn
5.显示目录：pwd
6.初始化git：git init           （.git有可能隐藏）
7.验证.git是否存在： ls -ah
8.添加learn到库：git add learn.txt
9.提交到库： git commit -m “改动的理由”
10.检测仓库当前状态： git status
11.检测仓库做过哪些修改：git diff learn.txt
12.查看修改历史： git log
13.只查看修改的提交信息： git log --pretty=online
14.回退到之前版本： git reset --hard HEAD^   (依次类推，最后一个版本是HEAD，上一个版本是HEAD^，上上个版本是HEAD^^，例如上100个版本为HEAD~100)
15.若命令行没有关闭，还可以回到已经退回的状态（即穿越过来还能再穿越回去）找到之前版本的版本号，git reset --hard 20930420（版本号，不用写全，能找到就行）
16.若命令行已经关闭，则用git reflog可以查看每一次的命令，命令里有版本号
