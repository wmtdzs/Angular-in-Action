# Angular-in-Action
Angular in action project<br>
这只是一个个人练习
# 创建项目
1. git clone git@github.com:wmtdzs/Angular-in-Action.git // 克隆项目<br>
2. cd Angular-in-Action // 进入项目<br>
3. git checkout -b <你的分支> // 建立本地开发分支<br>
# 如果想克隆后提交到自己的github上
1. git clone git@github.com:wmtdzs/Angular-in-Action.git // 克隆项目<br>
2. cd Angular-in-Action // 进入项目<br>
3. git remote add origin git@github.com:<你的用户名>/<你的项目名>.git // 添加远程仓库地址
4. git push -u origin master // 将本地主分支推送到远程
# 发布修改
1. git status // 查看修改<br>
2. git add . // 添加到库中<br>
3. git commit -am '提交描述' // 提交修改<br>
4. git fetch origin master:master // 捕获分支<br>
5. git rebase master // 合并代码，这里可能会产生合并操作<br>
6. git push origin <你的分支>:master // 提交到远程代码库
