# <a href="https://www.jianshu.com/p/6deca2cfc37a">Git前期配置的一些文章</a>
# 一些git的指令
查看所有远程分支             <br/>
$ git branch -a


# 步骤
1：先把项目clone到本地，在桌面用git base输入$git clone +项目的克隆ssh链接
克隆到本地以后，要打开项目的文件夹，再在里面运行git base
然后我们添加了一个叫test的txt文档，内容是Hello World

2： 在里面运行git base，输入$git add .            <br/>
这行命令的意思是添加新的文件到暂存区，也可以指定文件名来添加

3：$ git commit -m "备注描述文字"              <br/>
这行命令的意思是从暂存区提交到git管理区

提交到master分支，想要提交到哪个分支就$ git push origin 分支名字            <br/>
4：$ git push origin master  <br/>
   $ git push -u origin master          第一次发布的时候的语句
这行命令的意思是从git管理区push到远程仓库的master分支上
