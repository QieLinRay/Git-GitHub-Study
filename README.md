#  About GitHub----GitHub 相关

##### 开始加入Github不久，将在此记录和分享与Github有关的问题、信息、以及解决方案。希望能够帮到刚刚入门的各位。

##### I've recently joined GitHub and will use this platform to document and share information and solutions related to GitHub. I hope to assist those who are new to GitHub and provide helpful resources for them.

##### BTW,my English is poor. If you find any issues with my English expression, please feel free to point them out. I would greatly appreciate it!!!

### How to upload--提交的步骤(简易版本)

#### 1. Add ---添加

```bash

git add .  #添加所有文件--add all files
git add a.txt #添加a.txt--only add a.txt
```

#### 2. Commit---记录

```
git commit -m "commit name"  
#"commit name"用来记录你的操作，可自定义，the content in "commit name" is used to commit what you have done,you can replace it with anything you like(Best to related to your operation)
```



#### 3. Push---提交

```
git push origin main
(git push origin master)
#可能根据名字的不同，需要进行选择，一般为main，如果是master,git会提醒你的。
#Normally,the first one is right.Sometimes,it's the second.Just follow the suggestion git give you.
```

##### 以上三步只适用于在Github中将仓库已经clone在本地后，在该本地仓库中将修改的文件再上传到github中。

##### Attention!!!The 3 steps I mentioned above can only be done if you have already clone the repository in your own computer!!If you initial the repository in your PC at first and then do these steps,you can't upload the files to your github.(You can understand it as you don't have any connection between your PC and your github)

### How to download--下载的步骤

##### 在电脑相应的地址栏输入cmd.

##### Find the path you want to download the repositories,and input "cmd" in address bar to get into Console.

```
git clone 地址(Https or SSL from Repositories)（可以是Https,也可以是SSH）
```

