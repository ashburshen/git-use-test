本次测试：
1、在本地创建新文件夹：C:\Users\slt_u\Desktop\Gittest\Code-Git-Test1
2、进入Code-Git-Test1，在跟目录下git bash here，进行git init
3、添加一个readme的txt文件
4、尝试将这个本地Code-Git-Test1工作区添加暂存、提交、推送到github上，看是否能在没有该远程仓库的情况下推送到github
（github上没有预先创建名为Code-Git-Test1的仓库）

结论：github上没有目标仓库的话，push操作会失败，找不到目标仓库；
故应该在github上创建一个目标仓库，本地新仓库和远程仓库绑定，然后push