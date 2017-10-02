# Angular-in-Action
Angular in action project
----------------------------------
# 如何创建项目

# 复制项目
git clone git@github.com:wmtdzs/Angular-in-Action.git

# 进入项目
cd Angular-in-Action

# 建立自己的分支
git checkout -b topic/<自己的分支>
----------------------------------
# 如何提交修改

# 查看修改
git status

# 存入代码库
git add .

# 提交修改
git commit -am '提交描述' 
----------------------------------
# 如何发布修改

# 捕获分支
git fetch origin master:master

# 合并代码
git rebase master

# 发布到远程分支
git push origin topic/<自己的分支>:master
