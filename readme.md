# thinkbook 15 amd 完美黑苹果

## 电脑配置信息
型号: thinkbook 15 amd  
cpu: 4800u  
内存: 板载8G+扩展32G

## 黑苹果完美情况
10.13: 除了触摸板均正常  
10.14: 除了触摸板均正常  

### 硬件驱动情况

| 硬件 | 型号 | 工作情况 |
| :----: | :----: | :----: |
| cpu | 4800u | 已驱动 |
| 显卡 | 核显| 已驱动 |
| wifi |  | 已驱动 |
| 声卡 |  | 已驱动 |
| 休眠 | | 正常 |
| 触摸板| | 无法使用 |

## 使用说明
EFI 是安装后使用的,本身是 opencore,安装后复制到 EFI 分区,删除EFI分区的其他引导信息;  
EFI-INSTALL 是安装时,usb中使用的 opencore,之所以区分,是因为若安装时使用 EFI 则10.14会安装失败,10.13安装成功
拆分后,安装时用 EFI-INSTALL,安装后用 EFI

## 参考信息
[创建启动盘](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html#setting-up-the-installer)  
[ryzen-hackintosh](https://github.com/mikigal/ryzen-hackintosh)
[异常问题排查](https://dortania.github.io/OpenCore-Install-Guide/troubleshooting/extended/kernel-issues.html#stuck-on-eb-log-exitbs-start)
