# gitLibyrary
focus on git using


* 1. 新建三个分支 master(默认),develop,test,在本地develop分支开发，如果要合并到test分支，
需要到test分支使用git merge develop命令，把develop分支的代码合并到test分支，不是在develop分支直接合到test的（汇报Already Update To Date）。
* 2.本地分支master,develop,test如果都做了修改并且commit了（三者内容不一致）,
如果使用git push origin xxx 命令，不管当前分支是不是在xxx上面，提交的都是xxx分支的东西。

