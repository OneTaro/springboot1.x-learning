# springboot1.x 学习笔记

### git中忽略不需要上传的文件  
* 在idea中安装插件用来生成和管理 .gitignore 文件，安装成功后重启idea  
* 新建.gitignore 文件
* 将不需要提交的文件添加到.gitignore 

> .gitignore只能忽略那些原来没有被track的文件，如果某些文件已经被纳入了版本管理中，则修改.gitignore是无效的。那么解决方法就是先把本地缓存删除（改变成未track状态），然后再提交
