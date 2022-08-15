# fullbrowser.com

#### 简易的命令行入门教程:

Git 全局设置:

```
git config --global user.name "yangqing"
git config --global user.email "yangqingmv@qq.com"
```

创建 git 仓库:

```
mkdir fullbrowser.com
cd fullbrowser.com
git init 
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin https://gitee.com/gogv/fullbrowser.com.git
git push -u origin "master"
```

已有仓库?

```
cd existing_git_repo
git remote add origin https://gitee.com/gogv/fullbrowser.com.git
git push -u origin "master"
```

GitHub 上创建 git 仓库：

```
echo "# fullbrowser.com" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/gogv/fullbrowser.com.git
git push -u origin main
```