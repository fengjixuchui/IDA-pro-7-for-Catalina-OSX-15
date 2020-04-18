# IDA-pro-7-for-MAC-15-
## 起因
* IDA在MAC 10.15即Catalina上安装会报错，具体见https://www.52pojie.cn/thread-1063122-1-1.html
## 解决方案
* 在Mojave上安装之后拖入Catalina。
## 这个仓库的意义
* 提供一份本人已经在Mojave上安装好的IDA，亲测在Catalina上可用。
* 链接:https://pan.baidu.com/s/1trzbRcCL3YctQISGqPxvvg  密码:ode9
## 运行方式
* 下载并解压，点进文件夹后你可以发现一个替身`idabin`,点进替身，其中的可执行程序`ida`以及`ida64`正分别对应32位和64位ida的启动入口。
* 下面提出一种本人正在使用的方法。
  1. 使用MacOS的`自动操作`创建两个`应用程序`，这两个应用程序分别用来开起上述两个Unix可执行文件。
  2. 为了美观，本仓库提供32位与64位ida对应`icns`格式图标。
* 关于`自动操作`的创建以及图标的添加，可参考https://www.sqlsec.com/2019/11/macbp.html#toc-heading-9
