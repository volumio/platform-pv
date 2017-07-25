# platform-pv
Platform files for Polyvection's Voltastream Zero

Kernel Sources: https://github.com/PolyVection/linux-imx, branch imx_4.1.15_2.1.0_ga_PV  
U-Boot Sources: https://github.com/PolyVection/u-boot, branch v2017.05_PV  

This repo contains all files, used by the Volumio Builder to create a **Voltastream0** image

- kernel files (kernel, modules, firmware)
- u-boot (image, dtb, uenv.txt)
- other files. e.g. kernel configuration, initial patches for u-boot etc.)


**Files for Voltastream0, kernel version 4.1.15**
- 20170715: Initial, full Volumio 2 support on kernel 4.1.15  
- 20170719: Added getty on /dev/ttyGS0  
- 20170725: Added /etc/asound.conf (for ASRC support) to the platform files

