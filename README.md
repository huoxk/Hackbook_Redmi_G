# Hackbook_Redmi_G（2020款）

红米 G 游戏本通用

在MacOS Sequoia 15.8测试通过

## BIOS设置

快速启动 -> 关闭

CFG Lock -> 关闭 与 DVMT-Preallocated -> 64MB 可使用 Insyde H2OUVE 修改偏移值实现 （非必须修改）

### i5-10200H 版本的核显驱动后会花屏，目前无解！

## 进展

| 项目 | 状态 |
| ---- | ---- |
| 显卡加速 | 支持 |
| 独立显卡 | 支持 (请手动安装驱动)|
| 有线网络 | 支持 |
| 无线网络 | 支持 |
| 蓝牙 |已修复等待提交（此前无法连接HID设备） |
| HDMI (Type-C) 输出 | 理论支持但未测试 |
| 声音输出 | 支持 |
| 触控板 | 支持 |
| 电量显示 | 支持 |
| 亮度调节 | 支持 |
## 关于显卡
在制作EFI使用驱动版本为[1.13.0](https://github.com/nullmoth/nvidia-macos-driver/releases/tag/v1.13.0)测试一切正常
鉴于驱动更新很快，建议使用最新驱动[点击跳转](https://github.com/nullmoth/nvidia-macos-driver/releases)
可以使用1401安装驱动，亦使用离线版本安装
