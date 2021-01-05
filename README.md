型号：联想（Lenovo）拯救者 14.0英寸游戏本（i7-4720HQ 8G 128G SSD+1T GTX960M )
原配置如上。后来又加了根内存，机械盘换成了ssd。
## 特色
- 极简，几乎没有冗余的文件，完全从0开始使用OpenCore实现没有历史包袱。
带图形化启动菜单的EFI体积2.9M如下：


- EFI制作过程，全程记录。
[《手把手教你安装黑苹果之openCore-0.6.3 EFI制作全过程，非常详细》](https://blog.csdn.net/lxyoucan/article/details/110730680)
- 因为极简所有开机启动速度较快。
从open core的启动菜单按回车，到显示桌面（使用自动登录不用输密码）
我的电脑实测 ：
1.我的EFI开机启动大概 16秒左右。
2.github下载同机型的efi 启动速度大概 27秒左右。
这个大家可以自行测试，我没有必要报假数据。


## 目前成果
- 核显图形加速正常
- 声卡AppleALC实现，立体声正常
- 睡眠正常，唤醒正常，盒盖睡眠正常
- 蓝牙正常
- usb正常
- 键盘鼠标正常
- 有线网卡正常（内置的无线网卡无法驱动，无线网使用外接usb网卡）
- 摄像头正常
- 快捷键调节亮度正常
- HDMI正常
- 图形化启动界面，支持windows+macOS双系统启动
- 基于最新的open core 0.6.5实现（2021-01-05这个时间最新）
- 电池显示正常
- 触控板正常
- AppStore正常使用
- 支持HDMI音频。
如果不喜欢开始，关闭方法见：
[《OpenCore黑苹果之拯救者14（HD4600）开启HDMI音频》](https://blog.csdn.net/lxyoucan/article/details/111877620)
## 有待完善的
- 睡眠有很低的概率会出现自动唤醒 ，因为出现几率很低我不太好调试。后续观察中。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20201228230259266.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x4eW91Y2Fu,size_16,color_FFFFFF,t_70)

![电池正常](https://img-blog.csdnimg.cn/20201211001203529.png)
![触控板正常](https://img-blog.csdnimg.cn/20201211001217621.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x4eW91Y2Fu,size_16,color_FFFFFF,t_70)
![蓝牙正常](https://img-blog.csdnimg.cn/20201211001240901.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x4eW91Y2Fu,size_16,color_FFFFFF,t_70)
![有线网，无线网正常](https://img-blog.csdnimg.cn/20201211001401645.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x4eW91Y2Fu,size_16,color_FFFFFF,t_70)
![AppStore正常](https://img-blog.csdnimg.cn/20201211101814337.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x4eW91Y2Fu,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201222163956476.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2x4eW91Y2Fu,size_16,color_FFFFFF,t_70)
## 特别说明
此EFI首次在2020年12月11日开始使用，经过17天的测试，基本能够稳定运行。依然在完善中，是否需要下载自行判断。**制作不易，不喜勿喷。**

## 更新
2020年12月29更新
[https://download.csdn.net/download/lxyoucan/13980322](https://download.csdn.net/download/lxyoucan/13980322)

- 修复了在启动界面不显示Mac Install那个安装系统的图标
- 设置安装界面默认为中文
- 解决windows无法正常启动的问题

2021年1月5日更新
[https://download.csdn.net/download/lxyoucan/14029921](https://download.csdn.net/download/lxyoucan/14029921)

- 升级最新的OpenCore版本 0.6.5
- 优化启动项图标
- 解决某种特殊情况下，电池显示正在充电：1%
- 禁止OpenCore修改电脑启动顺序


### github
[https://github.com/lxyoucan/Lenovo-LEGION-i7-4720HQ-hd4600-14-OpenCore-Hackintosh](https://github.com/lxyoucan/Lenovo-LEGION-i7-4720HQ-hd4600-14-OpenCore-Hackintosh)
