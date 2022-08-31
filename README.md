Genesi efika mx patches
=======================

This repository contains patches for the Linux kernel to add support IMX51 Efika platforms from Genesi.

**For now it only supports TO2 platforms. Adding TO3 support (the one sold) should not be hard to do with proper platform. The hardware differences are small.**

It has been (briefly) tested on 6.0-rc3 on TO2 platform with original uboot and DTB appended.
The userspace part was Debian bullseye.

Several firmwares are needed. For instance, the GPU needs some. To avoid any license issue I won't provider here any firmwares. They can be found on the internet.

The GPU seems to work enough to get kmscube working. I've tested kmscube with 1024x768 and 1280x720 but it doesn't seem to like 1680x1050.
