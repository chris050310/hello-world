# hello-world
First repository

1.增加用户：useradd ming
2.增加用户组：groupadd users1
3.改变用户及用户组：chown ming:users1 test
4.ls开头的最近历史命令：!ls
5.chmod -R：级联改变，下面所有的文件都改变
6.lsattr: 显示特殊权限， chattr: 改变特殊权限
7.echo 'something' > 1.txt 重定向，等于是删除后增加
8.echo 'something' >> 1.txt 追加重定向，在最后增加
9.chattr +a 1.txt 不能修改，只能追加重定向。想去掉 chattr -a 1.txt
10.chattr +i 1.txt 更加严格，不能追加重定向。解除用-i
11.lsattr -R 级联查看
12.lsattr -d 只查看当前目录
