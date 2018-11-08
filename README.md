  # git常见命令
  ##  第一次运行
  * git config --global user.name"用户名"
  * git config --global user.email"邮箱"
  *  git init 初始化
  *  git add "文件名" .(是代表全部文件夹)
  *  git commit (后面可以接注释 v-"注释内容")
  *  git push (将本地文件放在远程文件上)

# 分支
+ 创建分支：git branch dev
+ 切换分支：git checkout dev
+ 创建+切换分支：git checkout -b dev
+ 查看当前分支：git branch
+ 切换回master分支：git checkout master
+ 合并指定分支到当前分支：git merge dev
+ 删除分支：git branch -d dev

# 远程仓库相关命令
- 检出仓库：$ git clone 
- 查看远程仓库：$ git remote -v
- 添加远程仓库：$ git remote add [name]
- 删除远程仓库：$ git remote rm [name]
- 修改远程仓库：$ git remote set-url
- 拉取远程仓库：$ git pull [remoteName] [localBranchName]
- 推送远程仓库：$ git push [remoteName] [localBranchName]


# 版本(tag)操作相关命令
1 查看版本：$ git tag
2 创建版本：$ git tag [name]
3 删除版本：$ git tag -d [name]
4 查看远程版本：$ git tag -r
5 创建远程版本(本地版本push到远程)：$ git push origin [name]
6 删除远程版本：$ git push origin :refs/tags/[name]


