TrueCrypt
=========

**TrueCrypt** project for windows version. It's just my **PRIVATE** version.


TrueCrypt compilable version, some minor adjustion for making vs2012 happy and not warning information. 
To compiling clearly, we need the following tools:

1. VS 2012 [download address](http://www.microsoft.com/en-us/download/details.aspx?id=12187)
2. nasm download [nasm](http://blog.tinybrowser.net/wp-content/uploads/2010/07/nasm.zip) . Then extract out file _nasm.exe_ and put it to system32(or SysWOW64) directory. 
3. gzip download [gzip](http://blog.tinybrowser.net/wp-content/uploads/2010/07/gzip.zip) . Then extract out file _gzip.exe_ and put it to system32(or SysWOW64) directory
4. vc1.5 [download](http://download.prjcode.com/detail/FWhWgTg) or [here](http://blog.tinybrowser.net/wp-content/uploads/2010/07/msvc-old-1-5.zip) . Then extract the .zip file to a folder, e.g. d:\vc1.5 , and create a environment variable MSVC16_ROOT = d:\vc1.5 . This is the last version c/c++ compiler that can generate 16 bit binary code.
5. WDK download [Microsoft provided](http://msdn.microsoft.com/en-US/windows/hardware/gg487428), After install the package, please create a environmant variable _BASEDIR_, e.g. BASEDIR = D:\WinDDK\7600.16385.1 . This tool can compile the driver.

