QR Code Generator Program
This is a program that generates QR codes.
Principle: It reads data in hexadecimal format and directly converts it into RGB values for storage.

Features:
I've added a few special characters as end markers (you can see them in the source code).

The last few digits indicate the file extension (suffix).

Technical Details:
Written in C++.

Uses SDL.dll (Why? Because I was too lazy to remove this dependency! 😛)

Path restrictions:

No Chinese characters or other full-width characters allowed.

Only standard ASCII-compatible paths are supported.

Performance Notes:
Not heavily optimized—conversion is slow for files ≥1MB.

Recommended for small files (KB-sized) for best performance.

Support:
If you have any questions or issues, feel free to ask me!



这是一个生成二维码的程序
原理就是16进制读入 直接转成RGB值存储
我添加了几个字符作为结尾标识符(你可以在源码中看到)同时最后几位指后缀
这是一个c++程序(你问我为什么需要sdl.dll?当然是我懒得去掉这个库了XP)
注意路径不能有中文等宽字符不允许的字符存在
我有点懒,没怎么做优化,>=1MB的文件转化速度很慢,推荐kb大小的文件做成二维码
有任何问题可以询问我
