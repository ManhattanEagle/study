查询某一天的前多少行日志

cat catalina.out \| grep "2017-03-05"\| head -n 1000



安装zip压缩解压程序

yum install -y unzip zip



tar -xzvf file.tar.gz  //解压tar.gz



zip -r mydata.zip mydata  //压缩mydata目录



rm -rf file  //删除文件夹

rm -f file  //删除文件



sudo su  //从普通角色切换至root

su supdev  //从root切换至普通角色



top  //查看进程、CPU使用率等



rz  //上传文件

rz -y  //上传文件，覆盖已有的相同文件



sz filename  //下载文件

sz -y filename  //下载文件，覆盖已有的相同文件



Ctrl + l  //清屏



vi 文本编辑命令：

:wq  //保存并退出

:1,.d  //删除从第一行到当前位置的内容  

