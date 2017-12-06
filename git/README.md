# git

## git 普通操作

````
git add .
git commit -m '[message]'
git push 
		<-f> // 强推
````



## git 分支

````
git branch 
git branch -a

git branch -r 
````

## git 拉取代码
```
git pull 拉取当前分支
git pull origin [远程分支] 拉取特定远程分支到当前本地分支
git pull origin [远程分支]:[本地分支] 拉取特定远程分支到特定本地分支
```

## git 合并代码

````
git merge branch // 合并某个分支到当前分支
git merge --no-ff branch // 合并某个分支到当前分支，保留原分支记录
````

## git 重置

````
git reset HEAD <file> 
git reset --hard [commitnum] // 强制回退到commitnum信息所在地址  //注意，此处push会报错，需要 git push -f
````


## git 标签

````
git tag
git tag -a [version] -m '[message]'
git push origin [version]
````