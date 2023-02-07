## 常用的linux命名
    1）  cd: 改变目录
    2）  cd.. 回退到上一个目录，直接cd进入默认目录
    3）  pwd 显示当前所在的目录路径
    4）  Is(II) 都是列出当前目录中的所有文件，只不过II列出的内容更加详细
    5）  touch 新建一个文件 如 touch index.js 就会在当下目录下新建一个index.js文件
    6）  rm 删除一个文件 如 rm index.js 就会把它删除
    7）  mkdir 新建一个文件夹
    8）  rm -r 删除一个文件夹 比如 rm -r src 删除src目录
    9）  mv 移动文件 比如 mv index.html src 而index.html是我们要移动的文件，src是目标文件夹
    10） reset 重新初始化终端/清屏
    11） clear 清屏
    12） history 查看命令历史
    13） help 帮助
    14） exit 退出
    15） # 表示注释

## git本地的三个工作区域
    1、工作目录(working Directory)
    2、暂存区(stage/index)
    3、资源库(Repository 或 Git Directory
    5、git远程仓库(Remote Directory)

## git 命令
    1、git init 初始化
    2、git clone [url] 克隆远程仓库
    2、git status 查看所有文件状态
    3、git add . 添加所有文件到暂存区
    4、git commit -m 提交暂存区的内容到本地仓库
    5、git push 将本地仓库上传

## git branch
    1、git branch [branch-name] 新建一个分支，但任然停留在当前分支
    2、git checkout -b [branch] 新建一个分支，并切换到该分支
    3、git merge [branch] 合并指定分支到当前分支
    4、git branch -d [branch-name] 删除分支
    5、git branch -dr [remote/branch] 删除远程分支
多个分支如果并行执行，代码也不会冲突，也就同时存在多个版本