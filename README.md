# 小米笔记本 Air 13.3 i7-8550U 四核八线程独显指纹 2018 款 EFI

本仓库用于存放黑苹果 EFI，会持续更新（如果有大佬更新的话）。  
本人没有什么黑苹果技术，资源都是白嫖其他大佬的，但是会一直测试整合最新最好用的此款笔记本 EFI 文件。

## 声明

目前所用 EFI 都是来自这位大佬[johnnync13](https://github.com/johnnync13/Xiaomi-Mi-Air)

## 硬件配置

- CPU：i7-8550U 四核八线程
- 核显：intel UHD Graphics 620
- 独显：GeForce MX150
- 内存：单条 8GB 2400 MHz DDR4
- 硬盘：主 250G SSD、副 240G SSD

## 目前系统

macOS Catalina 10.15.4

## 如何使用

暂时没空写，之后会补上

## 硬件支持情况

- CPU 睿频、变频
- 睡眠/唤醒
- 核显 HD Graphics 620 2048 MB
- 声卡，可通过快捷键 Fn-F2/F3 调节
- 触摸板 (多手势)
- HDMI 外置显示器（支持音频）
- USB 3.0
- 支持两个硬盘位
- 电池管理
- 内置摄像头
- 内置麦克风
- 内置蓝牙 (不支持隔空投送，支持随航)
- 支持快捷键 Fn-F4/F5 调节亮度
- iMessage，Siri 正常（[需要自行设置三码](https://www.tonymacx86.com/threads/an-idiots-guide-to-imessage.196827/)）

## 其他问题

- 独显无解
- Wi-Fi 有点小希望，有空再试试
- 连接外置显示器在启动时 logo 界面会闪一下
- 耳机孔连接音箱在启动时会有几声破音（可能是音箱供电口插在屏幕上都问题）
- Type-c 不知是否可以正常连接扩展坞
- 连接外置音箱可能会有滋滋电流声，下面有解决方案
- 指纹不能用，大佬说有希望

## 解决外置音箱滋滋电流声问题

在 `/Audio/ALCPlugFix_Xiaomi_Air_13_alc255Gen` 目录下运行终端，输入一下命令

```bash
bash install.sh
```
