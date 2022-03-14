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

### 撤销修改

git checkout -- <file name> // 可以撤销add之前的修改，也可以撤销add之后的修改

### 撤销添加到暂存区

git restore --stage <file name>

### 删除文件

1. git rm <file name>
2. git commit

### 添加远程库Github

1. 打开Git Bash创建SSH Key 

   ```bash
   ssh-keygen -t rsa -C "youremail@example.com"
   ```

2. GitHub上添加SSH Key

3. Github上创建一个新仓库

4. 在要上传的本地目录下

   ```bash
   git remote add origin git@github.com:michaelliao/learngit.git
   ```

5. 推送本地库内容到远程库

   ```bash
   git push -u origin master
   ```

### 从远程库克隆

从github上克隆仓库到本地

```bash
git clone git@github.com:michaelliao/gitskills.git
```

