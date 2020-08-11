111111

1、在本地修改文件；
2、git add .         全部添加
3、git status        可以看到已添加待提交的文件
4、git commit -m '版本说明'    提交后有记录，但是只存在了本地，之后可以回滚
5、git push origin motor_test   所有版本推到远端，同事可以访问
6、git pull origin motor_test  从远端拉下来（该分支motor_test的最新版本）
7、git log 查看该分支的所有版本
8、git checkout  cb98d95923e18ae00132a2d83646976d56c9c5db  commit之后回滚到之前的版本中
9 、git branch 可以查看分支
10、git checkout motor_test  切换分支 
11、git checkout .  放弃所有修改（对于已经划勾的文件，修改后，add之前，用该命令可以回滚到上次add的版本）
12、set https_proxy=http://127.0.0.1:10809   开启代理
13、Ctrl+c 退出当前命令