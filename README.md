# 网心云oes-a311d
所有内容均转载至恩山论坛，如有侵权请联系我删除。
网心云OES配置 主控：晶晨A311D 内存：4G EMMC硬盘:8G 千兆网口 x1 usb2.0 x1 SATA芯片：ASM1064 SATA口 x3
ubnutu刷机包：https://cloud.189.cn/t/aIbyQb6fuYNb（访问码：2bms）
ubnutu刷机方法：按住前面板的重启按钮，插入usb，链接电脑，用amlogic的USB_Burning_Tool 加载固件，提示SECURE_BOOT_SET 请将解压的SECURE_BOOT_SET文件拷贝到USB_Burning_Tool目录下的license文件夹内
在USB_Burning_Tool 的右边菜单  擦除flash 勾选，只能选普通擦除。这个包配置了无风扇的oes，刷完之后，你要使用风扇，请将你备份的boot分区内容，用dd重新写入boot分区，重启后自动生效。如果你没有安装昔映，且是第一次刷机，可以下载我的ubuntu.zip，解压后用dd刷写system分区，然后按住恢复出厂按钮，重新开机即可。

以上内容转载至恩山论坛，非本人创作。
