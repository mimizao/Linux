# /
根目录
## /bin
binary的缩写，里面存放二进制文件，也就是系统可执行程序存放目录
## /boot
内核和启动程序的相关文件都在此目录下
## /lib
library的缩写，库目录，主要存放系统最基本的动态数据库
## /media
自动挂载外接设备，挂载设备媒体，U盘，光驱等
## /mnt
该目录是为了让用户挂载别的文件系统，也就是和上面的自动挂载不同，手动挂载
## /usr
unix system resources的缩写，庞大和复杂的目录，很多程序会安装在这里  
用户自己安装的软件一般在/usr/local/目录下
## /sbin
比bin多了一个s，也就是super，超级管理员的执行程序，即root
## /proc
系统内存的映射，进程运行的一些信息会临时保存在这个目录下
## /etc
系统软件的启动和配置目录  
/etc/passwd 是用户存放文件，命令man 5 passwd可以查看文件格式
## /dev
device的简写设备文件所在目录  
**Linux一切皆文件**，就算是显示器都是，可以用ls /dev/命令查看，那些颜色黄的就都是
![dev文件夹](https://github.com/mimizao/Linux/blob/master/images/dev%E6%96%87%E4%BB%B6%E5%A4%B9.png)
## /home/user
用户家目录，后面的user就是用户名
