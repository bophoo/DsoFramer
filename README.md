# DsoFramer ActiveX Control
Exact from DsoFramer_KB311765_x86.exe, and re-format the source codes for more easily and clearly to read.

# 中文说明
## DsoFramer ActiveX 控件
从 DsoFramer_KB311765_x86.exe 里解压出来的，我把源代码格式化了一下，以便阅读和修改。

DsoFramer_KB311765_x86.exe 是 DSOFramer 控件的最新版（截止到2014年3月），网上没有比这个更新的了。微软官方开源的代码，已经不再更新了，下载连接也移除了，实际的最后更新时间大约是在2005年左右，所以相对来说，比较老。内嵌很方便，基本上能满足大部分需求，可以打开office 2007的各种文档，好像Office 2010也可以，但是我没试过。

## 其他说明

1.  原来的源码里Tab和空格都用了，所以我统一把tab字符转换为空格了（也是无奈）。因为有一些格式化是手工完成的，用VC自带的或其他软件格式化都有可能会有问题。
2.  .\Source_2008 目录下的是格式化后的 VS 2008 的工程，已经编译通过，你也可以转换为更高的VS版本，原来的工程好像是 VS 2005 的。
3.  .\Source 目录是原始的代码和工程，你可以跟 .\Source_2008 对比一下，看看格式化都变动了什么。
4.  Enjoy it!
