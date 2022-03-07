# Learn Git

## Git指令

### 初始化仓库

git init

### 添加文件到仓库

1. git add <file>	// 将文件提交到暂存区

2. git commit -m <message>    // 将暂存区的文件提交到分支

   ![image-20220307104943631](C:\Users\12524\learnGit\learnGit.assets\image-20220307104943631.png)

### 查看工作区状态

git status

### 查看修改内容

git diff

### 恢复到某个历史版本

git reset --hard <commitid> // head指针指向的版本就是当前版本

### 查看提交历史（历史版本）

git log

### 查看命令历史（做过哪些操作）

git reflog