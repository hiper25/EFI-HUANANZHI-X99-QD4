## HUANANZHI X99-QD4 Hackintosh

### 配置:

| 部件              | 规格                                    |
| ----------------- | --------------------------------------- |
| CPU               | Intel® Xeon® Processor E5-2630L v3      |
| 显卡              | AMD Radeon™RX 570 8G   B                | 
| 内存              | 4 * 16GB DDR4 2400Mhz                   |
| NVMe              | Kioxia RC10 1000GB                      |
| 有线网卡          | Realtek GBe Family (RTL8111)            |
| 声音              | Realtek ALC897                          |
| Wi-Fi & Bluetooth | BCM94360CS2 苹果拆机卡                  |
| SMBIOS            | MacPro7,1                               |
| 引导              | OpenCore 0.8.6                          |

### 可用:

- [x] AMD Radeon™RX 570
- [x] Broadcom BCM94360CS2
- [x] NVRAM
- [x] Realtek RTL8111 有线网卡
- [x] Realtek ALC897 声卡
- [x] USB 2.0/3.0
- [x] 传感器温度

- [x] macOS Monterey & macOS Ventura
- [x] Apple Music 支持无损或杜比音效带 AirPods 设备
- [x] Apple TV + 同上
- [x] DRM 内容（Netflix ATV+ Airplay 2 镜像等）
- [x] iCloud 所有功能（FaceTime iMessage等）
- [x] 完美的macOS OTA更新

### BIOS：

需要刷BIOS 
[点击这里](https://github.com/luchina-gabriel/EFI-HUANANZHI-X99-QD4-2630L-RX5500XT/tree/main/Artefacts/BIOS) 
进入BIOS 文件

"macOS.rom" 文件跟 "macOS-Unlocked-TB.rom"
区别就是后者是打过鸡血的文件

脚本： "./fptw64 -f macOS.rom -bios"


### 鸣谢：

- [OpenCore](https://github.com/acidanthera/OpenCorePkg)
- [luchina-gabriel](https://github.com/luchina-gabriel/EFI-HUANANZHI-X99-QD4-2630L-RX5500XT)
