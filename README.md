# 基本配置:
* cpu: i7-7560u
* 显卡：iris plus 640
* ssd：A400
* 网卡：943602BAED(DW1830, 该模块蓝牙芯片型号: BCM20703A1
* 分辨率：3200x1800
* BIOS 2.6.2
* 当前安装系统版本：10.13.4(17E199)

# 基本信息
* 雷电3可以热插拔
* 睡眠唤醒基本正常
* 外放&耳机正常运作
* 网卡免驱 蓝牙正常运行
* 唤醒不会出现蓝牙失效
* 触摸板/触屏 单点 双指（不支持缩放旋转）三指 手势正常 四指手势-呼出启动台不可以


# 注意事项：
* 已知问题：sd读卡器无法使用，触摸板无法支持缩放旋转手势，其它正常
* 安装好后，耳机无法使用的使用ALCPlugFix文件
* 如果感觉网卡无线频段不够的可以在config中的Boot参数Arguments中添加brcmfx-country=#a,同时添加网卡蓝牙目录下AirportBrcmFixup.kext驱动，重启即可
* LE文件夹可以使cpu多档变频以及低频支持（最低600，虽然设置最低400），变频有16档左右（具体忘记了），安装到系统的L/E文件夹下，重建缓存并重启，也就是hwp，仅i7-7560u使用

```
重建缓存命令：
sudo kextcache -i /
```
# 2018-04-12
* 更新Shiki.kext v2.2.5 解决 itunes 崩溃
* darkwake值设为1，经反复测试，唤醒不再黑屏（有背光）
* 设置了快速启动，按下电源键计算开机时间35秒左右。可在boot中修改参数，去掉fast选项后在timeout中设置超时时间
# 2018-04-07
* clover更新到4427

# Credit
* [hoanX](https://github.com/hoanX/xps13-9360-i7-7560u)
* [the-darkvoid](https://github.com/the-darkvoid/XPS9360-macOS)


