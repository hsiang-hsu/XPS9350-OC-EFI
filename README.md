# XPS9350-OC-EFI-Monterey 12.3.1
## 引导简介

……

## 硬件参数

- CPU：i7-6560U
- 显卡：HD540，Intel Iris Graphics 540
- 蓝牙：DW1820A
- 网卡：BCM4350
- 声卡：Realtek ALC256
- ……

## 正常工作

1. 显卡
2. 声卡
3. SD读卡器
4. 蓝牙
5. WiFi
6. 以太网
7. ……

## 不正常工作

1. 雷电口不能热插拔；
2. 右边USB口间歇性工作异常；
3. 隔空投送无法双向，目前只能iphone 到 mac；
3. 通用控制未实现；
3. ……；

## 需要修改

1. PlatformInfo->Generic->MLB：需要修改；
2. PlatformInfo->Generic->SystemProductName：需要修改；
3. PlatformInfo->Generic->SystemSerialNumber：需要修改；
4. PlatformInfo->Generic->SystemUUID：需要修改。
5. ……

## OC版本及更新日志

| 日期           | OC版本 | 系统版本        | 更新日志                                                     |
| -------------- | ------ | --------------- | ------------------------------------------------------------ |
| 2022年05月03日 | 0.7.9  | Monterey 12.3.1 | 修复核显1536MB->2048MB，增加framebuffer-unifiedmem --- 00000080 ---DATA |
| 2022年04月13日 | 0.7.9  | Monterey 12.3.1 | 修复SD读卡器，修复USB定制                                    |
| 2022年04月12日 | 0.7.9  | Monterey 12.3.1 | 正常引导                                                     |

## 特别感谢

1. https://github.com/danikpanik/XPS_13_9350_Monterey_Hackintosh
