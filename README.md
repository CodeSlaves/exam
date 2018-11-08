  # git常见命令
  ##  第一次运行
  * git config --global user.name"用户名"
  * git config --global user.email"邮箱"
  *  git init
  *  git add "文件名" .(是代表全部文件夹)
  *  git commit (后面可以接注释 v-"注释内容")
  *  git push (将本地文件放在远程文件上)

#分支
+创建分支：git branch dev
+切换分支：git checkout dev
+创建+切换分支：git checkout -b dev
+查看当前分支：git branch
+切换回master分支：git checkout master
+合并指定分支到当前分支：git merge dev
+删除分支：git branch -d dev
