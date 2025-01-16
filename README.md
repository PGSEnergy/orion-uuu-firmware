# orion-uuu-firmware
To change and rebuild u-boot.imx clone https://github.com/embeddedartists/uboot-imx and checkout to **ea_v2022.04** branch.

Usefull commands:
```
make mrproper
make mx6sxea-com_defconfig
make u-boot.imx CROSS_COMPILE=arm-poky-linux-gnueabi- -j$(nproc)
```
