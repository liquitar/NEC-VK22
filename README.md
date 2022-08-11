# NEC-VK22

## 简介

- NEC PC-VK22 ，基于OC包含基础驱动，修改三码后开箱即用。
- MAC版本：mojave


### EFI自测试硬件配置

NEC VK22

- Intel i5-5200U
- 4GB RAM (板载 )
- 2K屏
 
### SMBIOS MacBookAir7,2

### 硬件使用状态

* [x] 开机花屏，出现16个苹果，~~登录后合盖再开盖即可显示正常，或等几分钟屏幕自动熄屏后再唤醒也可显示正常（暂时还不知道是什么原因）~~换成OC 0.7.5 RELEASE后进入登录界面恢复正常
* [x] 集成显卡 Intel HD Graphics 5500 1536MB显存
* [x] 无线网
* [ ] 蓝牙 （USB内建后，蓝牙不可用了，内建前干扰太严重了，根本用不了，所以我现在用了一个外置USB蓝牙，B3526 CSR8510芯片，稳的一比）
* [x] 电池状态 （不完美，充电时显示充电中100%）
* [x] hidpi (1280*720 完美）
* [x] 声音
* [x] 触控板（多点触摸手势全开）
* [x] 声音快捷键正常，屏幕亮度快捷键变暗正常，变亮有问题，可在设置->屏幕中调节亮度
* [x] 休眠/唤醒/关机/重启 （电源LED、合盖/开盖全部状态正常）
* [x] USB正常


## 使用方法

- 复制EFI到EFI分区 编辑EFI/OC/config.plist 修改SystemSerialNumber、SystemUUID、MLB三码


## 必装工具 

- one-key-hidpi : 一键开启 macOS HiDPI
 

## 已知问题

               
## 致谢

- acidanthera https://github.com/acidanthera
- GITHUB中黑苹果的所有爱好者们
