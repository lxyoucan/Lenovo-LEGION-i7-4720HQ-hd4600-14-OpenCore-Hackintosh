型号：联想（Lenovo）拯救者 14.0英寸游戏本（i7-4720HQ 8G 128G SSD+1T GTX960M )
原配置如上。后来又加了根内存，机械盘换成了ssd。
## 特色
- 极简，几乎没有冗余的文件，完全从0开始使用OpenCore实现没有历史包袱。
带图形化启动菜单的EFI体积2.9M如下：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201211000633990.png)

- EFI制作过程，全程记录。
[《手把手教你安装黑苹果之openCore-0.6.3 EFI制作全过程，非常详细》](https://blog.csdn.net/lxyoucan/article/details/110730680)
- 因为极简所有开机启动速度较快。
从open core的启动菜单按回车，到显示桌面（使用自动登录不用输密码）
我的电脑实测 ：
1.我的EFI开机启动大概 16秒左右。
2.github下载同机型的efi 启动速度大概 27秒左右。
这个大家可以自行测试，我没有必要报假数据。


## 正常驱动的
- 核显图形加速正常
- 蓝牙正常
- usb正常
- 键盘鼠标正常
- 有线网卡正常（内置的无线网卡无法驱动，无线网使用外接usb网卡）
- HDMI正常
- 图形化启动界面，支持windows+macOS双系统启动
- 基于最新的open core 0.6.4实现（2020-12-11这个时间最新）
- 电池显示正常
- 触控板正常
- AppStore正常使用

![在这里插入图片描述](https://img-blog.csdnimg.cn/20201211001142418.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x4eW91Y2Fu,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201211001203529.png)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201211001217621.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x4eW91Y2Fu,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201211001240901.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x4eW91Y2Fu,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201211001401645.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x4eW91Y2Fu,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201211101814337.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x4eW91Y2Fu,size_16,color_FFFFFF,t_70)

## 特别说明
此EFI今天刚制作完成（2020年12月11日），没有经过长期的测试。是否需要下载自行判断。**制作不易，不喜勿喷。**

## 个人使用感受
之前用的是论坛里大佬分享的clover efi，外接HDMI显示器总觉得字体模糊。我这个版本不知道是不心理作用，感觉清晰一点了。

## 下载地址
[https://download.csdn.net/download/lxyoucan/13627320](https://download.csdn.net/download/lxyoucan/13627320)

