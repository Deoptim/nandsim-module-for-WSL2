# nandsim-module-for-WSL2
Usually, nandsim module inside package mtd-tools for creating raw nand dump images (with ecc or oob) for NAND-programmers. This repo contains kernel for 5.10.102.1-microsoft-standard-WSL2+ with support MTD partitions and external nandsim.ko module to use it with above description.

```
dmytro@DESKTOP-3P3B9MQ:~$ uname -a
Linux DESKTOP-3P3B9MQ 5.10.102.1-microsoft-standard-WSL2+ #5 SMP Mon Jul 11 14:04:13 EEST 2022 x86_64 x86_64 x86_64 GNU/Linux
```

How to manually build kernel for WSL2:
https://linuxtut.com/en/85707a56c31c1bb27b03/
