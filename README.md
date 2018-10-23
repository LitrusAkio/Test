# Test
git各种命令测试
# 步骤
1：先把项目clone到本地，在桌面用git base输入$git clone +项目的克隆ssh链接
克隆到本地以后，要打开项目的文件夹，再在里面运行git base
然后我们添加了一个叫test的txt文档，内容是Hello World

2： 在里面运行git base，输入$git add .
这行命令的意思是添加新的文件到暂存区，也可以指定文件名来添加

3：$ git commit -m "备注描述文字"
这行命令的意思是从暂存区提交到git管理区

4：$ git push origin master
   $ git push -u origin master          第一次发布的时候的语句
这行命令的意思是从git管理区push到远程仓库的master分支上
