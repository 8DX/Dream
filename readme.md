### 初识GitHub

###### 创建新储存库
---
**初始化git**
```
git init
```
---

**生成readme.md并输出# Dream**

```
echo "# Dream" >> readme.md
```
---

**将文件内容添加到暂存库**
语法：`git add [filename]`
添加readme.md到git暂存库
```
git add readme.md
```
---

**将更改记录提交到存储库**
语法：`git commit -m "提交说明"`
提交
```
git commit -m "first commit"
```
---

**添加远程仓库**
语法：`git remote add [repositoryname] [url/ssh]`
添加仓库名为origin路径为
`https://github.com/AdreamStudio/Dream.git的远程仓库`
```
git remote add origin https://github.com/AdreamStudio/Dream.git
```
---
**推送当前分支到origin master**
语法：`git push [repositoryname] [localbranchname]`

`-u` 推送分支master，同时指定origin为默认主机。
```
git push -u origin master
```
---
###### 推送现有储存库
```
git remote add origin https://github.com/AdreamStudio/Dream.git

git push -u origin master
```
---
##### 强制回退远程提交

```
git push origin HEAD --force 
```
---