# QEMU-on-OPENWRT
QEMU on OPENWRT
the project is to build a interface of controlling QEMU on LUCI based OpenWRT router system。
the functions contains list below， or more others that you can provide。

1.QEMU-img tool
2.qemu-bridge-helper tool
3.qemu-x86_64-softmmu tool


on the luci page, that can creat a img files, can creat snapshot, and use qemu-bridge-helper tool to bridge the network of Openwrt self.
qemu-x86_64-softmmu can select CPU number,type,machine type, add network nic devices,and mount iso files as cd-rom device on viertual machine.

also can list all viertual machine that has been created. and also can power on/off suspend.

and add VNC modle to the openwrt X86/64 system.
