下载镜像

下载rufuns 启动盘制作软件:双击直接运行rufuns。 设置分区类型MBR，文件系统FAT32，簇大小8192字节。

首先关闭win系统下的快速启动，开启快速启动有可能造成无法识别U盘。

然后关闭电脑，插入U盘，开机时快速按F2（不同电脑进入BIOS的按键不同，联想的大多为F2）进入BIOS设置。

进入BIOS设置后，切换到第 3 个选项卡 Security（安全选项），把 Secure Boot（ 安全启动 ）设置为 Disabled 。然后找到boot-USB boot-Enable开启USB设备引导。 F10保存并退出。

设置完成后，重新启动电脑，开机时长按F12进入Boot Manager，选中U盘启动。

姓名：吴浩正 学号：632004140531
