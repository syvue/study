**git常用命令**
> * 配置git用户名和密码
>     * git config  --global user.name sun
>     * git config  --global user.email  sun@qq.com
> * 查看当前git的配置
>     * git config --list
> * 初始化git 仓库
>     *  git init
> * 查看当前仓库的状态
>     * git status
> * 将工作目录中的文件添加到暂存区
>     * git add sun.html（这个命令上传一个文件）     git add  .(这个命令会将当前目标下所有文件上传)    git   add  a.txt  b.txt (如果上传多个，文件名之间用空格)
> *  将暂存区中的代码提交到本地仓库，形成一个版本
>     *  git  commit -m "备 注"（如果备注内容带空格，则需要加“”）
> * 查看本地仓库中的历史提交版本
>     * git  log
> * 用暂存区中的文件覆盖工作目录中的文件
>     * git  checkout -- 文件名
> * 回滚到本地仓库中特定版本并覆盖暂存区和工作目录
>     * git  reset --hard  commitID(commitID可以到git log中查看提交编号)，有种方式：1、全部黏贴  2、只取前6位