# gitcodetest

1. 查看项目的分支们(包括本地和远程) 
命令行 : $ git branch -a
2. 删除本地分支 
命令行 : $ git branch -d <BranchName>
3. 删除远程分支 
命令行 : $ git push origin --delete <BranchName>
4. 合并分支
git merge dev
5. 切换远程分支 
git checkout -b second-period origin/second-period
6. git fetch
7. git branch -va
8. 打tag
git tag -a v1.4 -m 'master'
9. 提交tag到远程
git push origin v1.5
git push origin --tags  一次推送所有本地新增的标签

10. 目前有两种查看文件修改记录方法:
一、git blame filename + git show commit-id
二、git log  filename + git show commit-id
