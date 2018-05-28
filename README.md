"# wp-downloadmanager_cn" 中文版

2018-05-28日更细说明日志。

本代码系统完全依据 wp-downloadmanager 基础上改写，请参考 https://github.com/lesterchan/wp-downloadmanager

此次主要考虑中文文件名附件的问题，毕竟文件过多的话，服务器端查找比较麻烦。。。。
英文文件名和目录不受任何影响

更新和升级内容如下

    1 完美支持中文文件名称，对所有已知的文件写入和写出过程都做了uft8和gb2313之间的转换。

    2 支持中文目录

    3 支持服务器中文列表的的正确读取
 
 
欢迎使用，测试服务器环境为中文 windows server 2008 r2上的wordpress平台

从系统道理上讲，这个版本应该放在linux系统的webserver上更好。因为linux对应的中文是gb2312编码，而windows实际是gbk编码。但是在windows系统下测试也没有问题。

如果发现还有文字转换问题，请提意见。miantuan@163.com

除了中文文字的支持意外，没有对其他功能做任何改动。

代码更新于一年以前，今日才更新说明，，，，太懒了。。。

