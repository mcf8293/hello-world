本地文件同步到github:(本地和远程已存在hello-world这个仓库)
1. git add 'a.txt'
2. git commit -m "new textfile"(new textfile为说明)
3. git push

本地项目同步到github:
1.在github新建一个仓库,并复制仓库地址(如:git@github.com:mcf8293/example.git)
2.在git文件夹下,右键git bash进入到git bash,然后执行
   git clone git@github.com:mcf8293/example.git
3.将项目文件夹(比如project)拷贝到example文件夹下
3.cd example/project
4.git add .
5.git commit -m "first commit"
6.git push -u origin master

gitHub远端操作:
1.建立repository
2.创建Branch分支
3.对文件进行更改
4.打开拉取请求
  new pull request/create pull request/
5.合并拉取请求
 Merge pull request/Delete branch

在工作目录中初始化新仓库
要对现有的某个项目开始用 Git 管理，只需到此项目所在的目录，执行：$ git init

克隆仓库的命令格式为 git clone [url]
比如，要克隆 Ruby 语言的 Git 代码仓库 Grit，可以用下面的命令：
$ git clone git://github.com/schacon/grit.git

跟踪新文件
使用命令 git add 开始跟踪一个新文件。所以，要跟踪 README 文件，运行：
$ git add README

提交更新
git commit

本地推送
git push


