#git 小测试

## git init 初始化
## 自报家门 
    + git config --global user.name "xiaoming"
    + git config --global user.email "573828395@qq.com"
##将代码放到仓库中区
    + git add ./readme.md 将文件放到仓库大门
    + git commit -m"我们完成了第一个功能"

### 若文件更新，则重复操作
    + git add ./readme.md  可以tab键自动补全
    + git add ./   把所有修改过的文件全部添加到大门口(暂存区)

### git commit -m "some message"
 + git commit --all -m "some message" 一次性将所有修改过的代码提交到版本库，无需经过暂存区， git add 和 git commit -m 功能合并的写法

##git 中的忽略文件
/.idea 会忽略 .idea 文件
/js  会忽略js目录里的所有文件
/js/*.js 会忽略js目录下所有js文件
node_modules/ 忽略node_modules 文件下的所有文件

##
#注释：
 + 工作区包括myproject，除了 .git 文件夹
 + 大门口又称暂存区，在 .git 里
 + .git 中的房间 又称为 版本库
 + git status 可以查看文件上传情况：绿色代表已经在暂存区，红色代表还在工作区,未放置大门口
 + clear 清除屏幕记录
 + git log / git log --oneline 查看git日志

 
