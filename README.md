## Thinkpad-T460p-opencore

#### 配置文件还有问题，不建议使用

* This repo is based on : [Thinkpad-T460p-OSX-EFI](https://github.com/totemofwolf/Thinkpad-T460p-OSX-EFI)&&[ThinkPad-T460s-macOS-OpenCore](https://github.com/simprecicchiani/ThinkPad-T460s-macOS-OpenCore)

可以使用[ThinkPad-T460s-macOS-OpenCore](https://github.com/simprecicchiani/ThinkPad-T460s-macOS-OpenCore)的配置文件，能够启动，但USB有问题

| *项目*     | *工作与否* |                            *备注*                            |
| ---------- | :--------: | :----------------------------------------------------------: |
| CPU变频    |     √      |             系统默认变频， i7-6700HQ, 0x191b0000             |
| SMBios     |     √      |                           MBP13,3                            |
| 🔊声卡      |     √      |            ALC-293(无法使用时可以尝试reset nvram)            |
| 显卡       |     √      |                      Intel HD530 @1080p                      |
| HDMI       |     X      |                         内建屏幕黑屏                         |
| 有线网卡   |     √      |                        Intel I219LM2                         |
| WiFi       |     √      |                           AC 8260                            |
| 📹摄像头    |     √      |                                                              |
| USB-3.0    |     x      |            速度:最大 5 Gb/秒，右下USB只能使用2.0             |
| 🔋电池      |     √      |           我的电池接近报废，无法判断是否能正常工作           |
| 亮度快捷键 |     √      |                            F5,F6                             |
| 声音快捷键 |     √      |                            F2,F3                             |
| 触摸板     |     √      |                                                              |
| HIDPI      |     √      | [one-key-hidpi]([xzhih/one-key-hidpi: Enable macOS HiDPI and have a native setting. (github.com)](https://github.com/xzhih/one-key-hidpi)) |

> 安装时将ig-platform-id改为0x12345678（必须改，空着也不行！）并且设置啰嗦启动(-v)模式进入安装

