# GitText 
## 场景
### 1.拉取远程仓库 到 本地仓库
克隆仓库\
git clone git@github.com:Rise-sc/Git-Test.git\
创建分支\
git branch dev\
git switch dev\

### 2.本地仓库 push 远程仓库/空仓库
添加远程仓库地址\
git remote add origin git@github.com:Rise-sc/Git-Test.git\
查看远程仓库地址\
git remote -v\
指定分支为main\
git branch -Mmain\
推送(若是推送其他平台,修改origin,gitlab,giteed等)\
git push -u origin main\
git push -f origin main (这个本地分支直接覆盖远程分支)\
注意: 若是远程仓库为空可以这样子使用, 若是远程仓库有文件,则会失败,git允许同时存在两个主分支.\

### 3.基本命令
对git默认改名\ 
git branch -m main dev\
对git默认改名全局\
git config --global init.defaultBranch main\
 


 
