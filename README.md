TrueCrypt
=========

TrueCrypt project for windows version. My private version.


TrueCrypt 可编译版本, 主要做了一些微调, 使得能通过vs2012, 并且不再吐出警告信息, 要完整编译本源代码, 需要自己下载以下编译工具:

    VS 2012 [download address](http://www.microsoft.com/en-us/download/details.aspx?id=12187)

    nasm 下载地址 [nasm](http://blog.tinybrowser.net/wp-content/uploads/2010/07/nasm.zip) 下载后将 nasm.exe 文件解压出来, 放到 system32 目录里

    gzip 下载地址 [gzip](http://blog.tinybrowser.net/wp-content/uploads/2010/07/gzip.zip) 下载后将 gzip.exe 文件解压出来, 放到 system32 目录里

    vc1.5 [下载地址](http://download.prjcode.com/detail/FWhWgTg) 或 [这里](http://blog.tinybrowser.net/wp-content/uploads/2010/07/msvc-old-1-5.zip) 下载后解压到一个文件夹, 如 d:\vc1.5 , 然后创建一个环境变量 MSVC16_ROOT = d:\vc1.5 这是微软提供的最后一个能生成 16 位代码的编译工具

    WDK 下载地址 [微软提供](http://msdn.microsoft.com/en-US/windows/hardware/gg487428), 安装后用目标目录创建环境变量 BASEDIR, 如 BASEDIR = D:\WinDDK\7600.16385.1 这个工具用于编译驱动

