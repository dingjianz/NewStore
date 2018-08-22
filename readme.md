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

### git commit -m "some message"

#注释：
 + 工作区包括myproject，除了 .git 文件夹
 + 大门口又称暂存区，在 .git 里
 + .git 中的房间 又称为 版本库
 + git status 可以查看文件上传情况：绿色代表已经在暂存区，红色代表还在工作区,未放置大门口