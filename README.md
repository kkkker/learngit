1. 

```
git init
git remote add origin https://github.com/kkkker/learngit.git
git add --all
git commit -m "[Mamingjun]: first add"
git push origin master
```

2. 

```
git clone -b dev https://github.com/kkkker/learngit.git
git checkout -b feature-1
git switch -c feature-1
git push origin feature-1
```

3. 

```
A:git clone origin [分支名]
B:git clone origin [分支名]

A:编写完测试之后
git add --all
git commit -m ""
git pull origin [分支名]
git push origin [分支名]

B:git pull origin [分支名]
编写实现
git add --all
git commit -m ""
git pull origin [分支名]
git push origin [分支名]
```

4. 

```
git reset --hard HEAD~2
git reflog
```

