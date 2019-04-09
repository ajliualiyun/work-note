# 常见问题汇总

* 1. MAVEN依赖包问题

     问题描述： maven工程在eclipse中找不到对应的依赖包，而且本地依赖包确实存在，其错误如下图所示

     ![](<https://github.com/ajliualiyun/work-note/blob/master/maven/pic/question01.bmp>)

     问题解决：将有问题的依赖包所对应的本地路径不相关的文件删除即可解决每次都要从远程maven仓库中加载的问题：如下图

     ![](E:\gitbook\maven\pic\question02.bmp)

     ​	![](E:\gitbook\maven\pic\question03.bmp.png)

