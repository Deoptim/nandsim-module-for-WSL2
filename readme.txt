In WSL2
=================
sudo mkdir /lib/modules/5.10.102.1-microsoft-standard-WSL2+
sudo cp <path to file>/nandsim.ko /lib/modules/5.10.102.1-microsoft-standard-WSL2+/
sudo touch /lib/modules/5.10.102.1-microsoft-standard-WSL2+/modules.order
sudo touch /lib/modules/5.10.102.1-microsoft-standard-WSL2+/modules.builtin
sudo depmod
====================================================================================
In file .wslconfig
==================
[wsl2]
kernel=c:\\wslkernel\\kernel-5.1.0-nandsim