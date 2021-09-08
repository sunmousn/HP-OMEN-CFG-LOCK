# HP-OMEN-CFG-LOCK
## [建议参考使用CFGLock.efi快速解锁](https://blog.daliansky.net/undefined.html)  
### 查看CFG LOCK解锁状态  
如果Hackintool没有输出数据无法查看CFG LOCK是否解锁可使用/EFI/OC/Tools目录下的ControlMsrE2.efi进行查看，将ControlMsrE2.efi添加到config并启用，重启选择ControlMsrE2回车最后一行显示This firmware has UNLOCKED MSR 0xE2 register!即为解锁状态
### 解除CFG LOCK锁定
![image](https://user-images.githubusercontent.com/35004454/131802963-db4d81b2-c7c0-469d-82ed-8d063746fd1e.png)
