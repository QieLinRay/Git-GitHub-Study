## GitStudy（基础向）

​	由于自身对不管是git还是github都处于一种一知半解的状态，这种状态在我每一次打开github时都会感觉到不适，所以花了一点时间来学习一下Git。如果你跟我一样，非科班，但由于兴趣使然，想要了解或者学习一些有趣的东西，那就继续看下去吧。

​	在本次分享中，首先，将分享自己在这次学习中找到的相关学习资料；其次，将自己最近学习的相关Git的知识进行总结（基础性），主要是希望将相关知识进行内化。在知识爆炸的今天，如果我的分享能够给你带来一点点帮助或者有一点点其实，那将感到非常荣幸。

​	

1. #### 资源分享

   - [B站：狂神说Java--Git最新教程通俗易懂](https://www.bilibili.com/video/BV1FE411P7B3/?spm_id_from=333.999.0.0&vd_source=7e7a4cc38d46122b5ce881167d8b1eb4)：本教程如果静下心来，也就一个晚上的时间能够听完，作为Git的入门教程来说，个人听下来不算难，就像标题说的一样确实通俗易懂。教程从版本控制，Git的基础操作，SSH配置，远程仓库的建立都有涉及。但从Git应用角度而言，个人感觉是够用的。（毕竟大部分时候只需要clone,add,commit,push,pull就够了hhhhh)但是该课程对于分支的讲解不是很好，建议直接跳过。
   - [Git分支讲解](https://www.bilibili.com/video/BV16M411z7uH/?spm_id_from=333.337.search-card.all.click&vd_source=7e7a4cc38d46122b5ce881167d8b1eb4)该视频对分支的讲解较为清晰明了，可以参考学习。

   - [廖雪峰的官方网站--Git教程](https://www.liaoxuefeng.com/wiki/896043488029600)教程本身非常优秀，并且在下面的交流区的友友都非常的nice,有什么问题可以相互交流。

   - [Git官方命令大全](https://git-scm.com/docs)里面给出了全部的git命令，但是由于是英文版，所以可能对某些小伙伴来说可能不太友好。(不过都已经进CS的坑了，怎么能逃得出英语!!)没事的话可以按照上面的命令一个一个试试。

   - [Gitee官网](https://gitee.com/explore)在Gitee下方（鼠标拉到最下面）有相关Git的相关学习资源，非常的全面。

     ![Gitee](D:\AAGitHub_file\About-GitHub\Pictures\Gitee.png)

     

2. #### Git知识点总结

   ​	在了解完Git的历史之后，在开始总结之前，还是想感叹一下Linus Benedict Torvalds的天赋。有些人就是为改变世界而存在的吧。

   ​	（注：以下总结的文字部分可能和专业有一定差异，主要是用于辅助记忆的自我理解）

   **小Tips:**

   - 按住**Ctrl+鼠标滚轮**，可以调整Git bash的字体大小。

   - clear操作可以清屏

     

   #### 总结

   - **分布式版本控制器**

     ​	Git是分布式版本控制系统。与集中式的版本控制系统（如SVN）相比，分布式版本控制系统没有所谓的“中央服务器”的概念，每台服务器上都有完整的版本库。这就保证了当某一台服务器出现问题的时候，不会影响到其他服务器上的开发。

   - **历史**

     ​	1.与初期Linux的维护有着密不可分的原因；

     ​	2.Linus Benedict Torvalds在与BitKeeper终止合作后花了**两个星期**开发了Git。

   - **Git的安装**

     在网上关于Git的安装讲解已经很详细了，具体可以自行搜索即可。以下给出一个教程与官网下载地址。

     [Git安装教程](https://zhuanlan.zhihu.com/p/242540359)

     [Git下载官网](https://git-scm.com/downloads)

     在完成安装后的第一步，一定要配置用户名和邮箱。因为Git是分布式版本管理，所以相当于需要自报家门。也就是在完成安装后，需要在git bash中输入以下代码进行配置

     ```bash
     $ git config --global user.name "name" #name为你自己取的用户名
     $ git config --global user.email "email address" #email address 为你自己的邮箱地址
     ```

     在配置好上述信息后，在本地C盘用户下可以找到相关的配置文件（.gitconfig)

     或者也可以通过以下代码查看相关的配置

     ```bash
     $ git config --global -l
     
     ```

     

   - ##### **Git命令**

     （明天再更）

