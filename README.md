# EFI-OC_067-MSI_MAG_B460M_MORTAR_WIFI-intel_10700-iGpu_UHD630
EFI-OC_067-MSI_MAG_B460M_MORTAR_WIFI-intel_10700-iGpu_UHD630

<img src="https://tva1.sinaimg.cn/large/008eGmZEgy1gpfxmqtw1zj31hc0u04qz.jpg" style="zoom: 50%;" />





## 状态

USB 映射OK，USB 2，USB 3，Type C----------------------- OK

蓝牙----------------------------------------------------------------OK

<img src="https://tva1.sinaimg.cn/large/008eGmZEgy1gpfxshckkqj30gk0kstbe.jpg" style="zoom:33%;" />



**BIOS里关闭usb唤醒，不然睡眠不了，关闭后usb键盘鼠标就不能再睡眠后唤醒，但是可以按开机键唤醒。**     



## 配置

​	**OpenCore 0.6.7**

​	**CPU**：Intel 10700

​	**CPU散热**：利民 FS140

​	**主板**：MSI MAG B460M MORTAR WIFI

​	**显卡**：CPU自带的集显 UHD 630

​	**机箱**：先马（SAMA）平头哥M1(商务版)，机箱前面带2个USB 2接口，1个USB 3接口。USB-Map.kext中需要根据机箱和主板上具体的USB接口调整，机箱后端USB接口为主板USB接口。

​	**Wifi+蓝牙**：BCM94360CD **免驱**

​	**硬盘**：WesternDigital 西部数据 SSD 1T M.2（NVMe） Blue SN550 +  Crucial 英睿达 500G SSD SATA 3.0 MX500

​	**内存**：Crucial 英睿达 8GX2 DDR4 3200

​	**显示器**：DELL U2720QM显示器 4K，**使用DP线连接主板集显输出**，如使用HDMI线连接显示器，参考安装连接里的可能需要增加些配置

​	**电源**：安钛克 Antec HCG650金牌全模



## 安装

能翻墙的直接-很全面（中英文资料届差距确实大，这种完整成体系的中文基本没有，都是零散的）：

https://dortania.github.io/OpenCore-Install-Guide/







