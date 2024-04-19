# 微星 GF75 Thin 8RD 黑苹果 Clover EFI

基于 [Dimon70007](https://github.com/Dimon70007) 的项目修改

已支持 MacOS Sonoma 14.4，附有 [MacOS 安装教程](https://1doublehelix.github.io/msi-gf75-hackintosh.html)，旧版 MacOS 请到 [release](https://github.com/1DoubleHelix/MSI-GF75-8RD-Clover-EFI/releases) 下载

## 重要提示

- 理论上本项目的 EFI 可以启动 BigSur 到 Sonoma 14.4 的所有版本，但是需要替换 `Clover/kexts/Other/AirportItlwm.kext` 为对应版本的 kext，具体请参考 [OpenIntelWireless/itlwm/releases](https://github.com/OpenIntelWireless/itlwm/releases) 下载对应版本的 kext，目前需要使用 alpha 版本的 kext
- 本项目即将存档，不再更新

## 部分硬件

- Intel Core i5-8300H
- Intel UHD 630
- NVIDIA GeForce GTX 1050ti
- 16GB 内存（8GB*2）
- 铠侠 RC20 500GB NVMe SSD
- Realtek PCIe GbE 有线网卡
- Intel AC 9462 无线网卡

## 工作正常

- Intel UHD 630
- HDMI 仅视频
- 英特尔无线网卡
- 瑞昱有线网卡（RJ45）
- 有线麦克风和耳机
- 显示器亮度调整
- 电池信息
- USB 3.0（包括 Type-C）
- voodoops2controller 的板载键盘和触摸板
- 摄像头（通过热键启用/禁用）

## Bug

- HDMI 无音频
- NVIDIA 独显不工作
- 无法从三星 980 SSD 启动 Clover
- Type C 端口仅在 USB 3.0 速度下工作
