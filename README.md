# SMx
国产加密算法 SMx 
## SM2
椭圆曲线公钥加密算法
## SM3
HASH摘要算法

这里要注意 long, 在 windows64平台下占用4个字节 ；
而long, 在linux64平台下占用8个字节；
这种差异直接导致了windows和linux结果的差异；
解决方式就是，修改sm3.cpp，将所有unsigned long 改成 unsigned int;
这样即支持linux和windows平台就保持一致了；
## SM4
分组对称加密算法
## doc
标准与说明文档


