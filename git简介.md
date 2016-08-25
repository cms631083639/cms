## Git

### 代码量不多，没有必要备份

### 什么是Git?
  - Git是一款源代码管理工具(版本控制工具)
    - 我们写的代码需要使用Git进行管理。
  - 手写的代码
  - 源代码有必要管理起吗？
  - svn,vcs,vss
  - 有必要，因为人工的去处理不同的版本，做相应备份会很麻烦。

  -Git是linux之父当年为了维护linux---linus之前也是手动维护合并把文件发给Linus
  - BitKeeper(收费)
  - 有人想破解(不给提供免费使用)
  - linus自己写了一个版本管理的工具（Git）


### 分布式，集中式
  - 分布式版本管理工具   可以在本地提交.
  - 

### git提交代码流程 
  1.首先把代码添加到暂存区
    + 命令: `git add [文件路径]`
  2.把代码从暂存区提交到仓库
    + 命令: `git commit -m "[一些注释]"`
  3.可以配合`git status`命令来使用.

### git自报家门
  - 命令:`git config user.name "testName" `
    + 这个命令是用来配置用户名的
  - 命令:`git config user.email "test@isc.com"`
    + 这个命令是用来配置用户邮箱的.

  - 如果需要进行全局配置，直接加上--global参数就可以
    + `git config --global user.name "testName"`
  - 查看配置信息
    + `git config list`

### 