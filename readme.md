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

## 会退到指定的版本
    - git reset --hard Head~0 表示会退到上一次提交代码时的状态
    - git reset --hard Head~1 表示回退到上上次提交代码时的状态
    - git reset --hard 版本号  根据版本号会退到对应的状态


## 默认有一个主分支master
###创建一个dev分支 git branch dev
+ 刚创建时dev分支里的的内容和master分支里的内容是一样的
### 切换分支
-git checkout dev
    + 切换到指定的分支，这里切换到名为dev的分支
    + git branch 可以查看当前 .git仓库中有哪些分支

###合并分支
- git merge dev 
    + 合并分支内容，把当前分支与指定的分支(dev),进行合并(切换至master后再进行合并)
    + 当前分支指的是 git branch 命令输出的前面有 * 号的分支

### 删除分支(注意：不能自杀，只能别人删除)
    - git branch -d dev 删除 dev 分支

## 提交代码到github（当作git服务器来用）
    - git push 【地址】 master ： git push https://github.com/dingjianz/NewStore.git master
        + 会把当前分支的内容上传到远程的master分支上

#注释：
 + 工作区包括myproject，除了 .git 文件夹
 + 大门口又称暂存区，在 .git 里
 + .git 中的房间 又称为 版本库
 + git status 可以查看文件上传情况：绿色代表已经在暂存区，红色代表还在工作区,未放置大门口
 + clear 清除屏幕记录
 + git log / git log --oneline 查看git日志
 + git reflog  可以看到每一次切换版本的记录

 

