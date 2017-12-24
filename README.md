This is the source tree of U-Boot, a popular boot loader for embedded devices. U-Boot was developed by DENX Software Engineering (www.denx.de).

This particular version of U-Boot supports several Cortex-M3 and Cortex-M4 based MCUs.

Prerequisites
=========
Please read [Default Setup](https://github.com/mehmetalinbay/uclinux/blob/master/default_setup_README.md)

Download U-Boot
=========
```
  cd ~/workspace
  mkdir boot
  cd boot
  git clone https://github.com/mehmetalinbay/u-boot.git
```
Compiling
=========
```
  make ARCH=arm CROSS_COMPILE=arm-uclinuxeabi- O=stm32429-disco stm32429-disco
```

