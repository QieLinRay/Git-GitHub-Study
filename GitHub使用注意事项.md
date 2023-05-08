## GitHub使用过程中相关问题以及解决方法

以下为自身使用GitHub过程中遇到的问题以及相关解决方法。

#### 1.Git push origin main出现Timeout超时的现象

情况描述：在保证网络通畅的情况下在github上上传和下载均失败。

解决途径：在git中设置代理。

**详细步骤：**

1.首先找到本机的代理服务器地址以及端口

（windows左下角搜索框输入“代理服务器”即可查看地址和端口）

2.在对应地址栏输入cmd进入控制台

3.输入以下命令：

git config --global https.proxy https://地址:本机端口

git config --global http.proxy http://地址:本机端口

**需要注意的是端口一定需要是本机端口！！才可以**

输入上述命令后，cmd没有回应，不用担心，表示其添加成功

4.在cmd中输入git config --global  --list便可以查看是否添加成功

5.重新尝试clone和push即可

#### 2.不使用SSH在本地以及GitHub上同步文件的方法

在网上看到将本地文件同步上传的方法有一点复杂，本人采取方式为，在github上先创建一个repo,然后将该repo clone到本地，然后在本地正常进行add ,commit,push操作即可。





