# **git-book git 命令行使用手册**

### 1、常用命令
---
>git init 初始化仓库，不对文件夹进行该命令则无法使用git进行版本控制  
git status 仓库状态，显示当前分支，提交状态。  
git add 添加文件到暂存区，git此时会将提交的文件作为版本管理对象纳入管理
git commit  将暂存区文件 保存到仓库中，同时会记录变动的文件。后期如有需要可以进行恢复。
git log 查看提交日志  
    |    --pretty =short 简述 日志  |  
    |     特定文件          |  
    |    -p 提交带来的变动  |  
git diff 查看工作树与暂存区的差别 + 添加的 - 删除的
git checkout - 切换上一个分支
git checkout -b 创建 切换分支
git merge 合并分支
git reflog 查看仓库的历史操作日志
git commit -amend 修改提交信息
git rebase -i 压缩历史 == add + commmit
git remote add reposname git@github.com: username/reposname 添加远程库名字
git push 推送远程仓库 git push -u reposname main（分支名字）
git clone 获取远程仓库
git pull 获取最新的远程仓库分支