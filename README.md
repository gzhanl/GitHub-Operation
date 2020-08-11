# GitHub-Operation
Git Hub 一般操作

## 1. 將現有文件夾上傳到GitHub步驟
1.git init   
在AAA文件夾裡 Gitbash , git init 文件夾  


2.git add * (將全部文件git add 管理)

git status 可以查看到，已將所有文件 git add 進資料夾


3.git commit -m （一次commit加入所有文件）

4.在github 網站新增遠程倉庫


5.添加遠程倉庫
$ git remote add origin git@github.com:gzhanl/AAA.git

6.git push 推送至遠程倉庫

完成。


## 2.修改本地代码并同步上傳到GitHub  
1.git add (-A /-u /.)  
· git add -A 提交所有变化   
· git add -u 提交被修改(modified)和被删除(deleted)文件，不包括新文件(new)   
· git add . 提交新文件(new)和被修改(modified)文件，不包括被删除(deleted)文件  

2.git commit -m '.......'

3.git push -u origin master

## 3.修改远程代码后同步到本地仓库

例如我修改了 readme.md

1.git fetch origin  
2.git merge origin/master  

## 4.放弃本地的修改，不commit,直接pull最新代码
1.git fetch --all //从远程拉取所有内容  
2.git reset --hard origin/master //reset 本地代码    
3.git pull //重启拉取对齐 



