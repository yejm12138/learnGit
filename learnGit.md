### 参考链接
https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners  
### 基本流程  
初始化仓库 git init  
将文件的变动加入 stage 环境 git add  
将 stage 环境中的变动打包成一个 commit git commit  
### 分支
创建一个新分支 git branch "branch name"  
切换到一个分支 git checkout "branch name"  
简洁方式 git checkout -b "branch name"  
### github 远端仓库
在 github 上创建一个仓库  
为本地仓库加一个远端仓库 git remote add "remote name" "remote url", remote name 实际上是为 remote url 创建的一个别名    
将本地的提交推送到远端仓库 git push "remote name" "branch name", github 会自动为远端仓库创建分支  
### pr
向远端推送分支, 创建 pr, 合并 pr  
与远端 master 分支同步 git pull origin master  

如果没有向远端仓库推送的权限, 提交 pr 的步骤  
fork, git clone 到本地, 推送分支, 创建 pr, 等待合并  

e