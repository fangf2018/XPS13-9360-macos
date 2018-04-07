# XPS13-9360-Hackintosh-10.13.x
# 基本配置:
* cpu: i7-7560u
* 显卡：iris plus 640
* ssd：A400
* 网卡：dw830
* 分辨率：3200x1800
* BIOS 2.6.2
* 当前安装系统版本：10.13.4(17E199)

# 注意事项：
* 已知问题：sd读卡器无法使用，触摸板无法支持缩放旋转手势，其它正常
* 安装好后，耳机无法使用的使用ALCPlugFix文件
* 如果感觉网卡无线频段不够的可以在config中的Boot参数Arguments中添加brcmfx-country=#a,同时添加网卡蓝牙目录下AirportBrcmFixup.kext驱动，重启即可
* LE文件夹可以使cpu多档变频以及低频支持（最低600，虽然设置最低400），变频有16档左右（具体忘记了），安装到系统的L/E文件夹下，重建缓存并重启，也就是hwp，仅i7-7560u使用

# 2018-04-07
* clover更新到4427
* 关机不再丢失蓝牙

# Credit
* [hoanX](https://github.com/hoanX/xps13-9360-i7-7560u)
* [the-darkvoid](https://github.com/the-darkvoid/XPS9360-macOS)
