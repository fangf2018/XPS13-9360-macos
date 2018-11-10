# 基本配置:1111
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
* 如果感觉网卡无线频段不够的可以在config中的Boot参数Arguments中添加brcmfx-country=#a,

```
重建缓存命令：
sudo kextcache -i /
```

# Credit
* [hoanX](https://github.com/hoanX/xps13-9360-i7-7560u)
* [the-darkvoid](https://github.com/the-darkvoid/XPS9360-macOS)


