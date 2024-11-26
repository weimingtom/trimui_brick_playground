Microsoft Windows [版本 10.0.19045.5131]
(c) Microsoft Corporation。保留所有权利。

D:\adt-bundle-windows-x86-20140624\sdk\platform-tools>adb shell


BusyBox v1.27.2 () built-in shell (ash)

 _____  _              __     _
|_   _||_| ___  _ _   |  |   |_| ___  _ _  _ _
  | |   _ |   ||   |  |  |__ | ||   || | ||_'_|
  | |  | || | || _ |  |_____||_||_|_||___||_,_|
  |_|  |_||_|_||_|_|  Tina is Based on OpenWrt!
 ----------------------------------------------
 Tina Linux (Neptune, 5C1C9C53)
 ----------------------------------------------
root@TinaLinux:/# exit
exit

D:\adt-bundle-windows-x86-20140624\sdk\platform-tools>adb push evtest /mnt/SDCARD/
1652 KB/s (49824 bytes in 0.029s)

D:\adt-bundle-windows-x86-20140624\sdk\platform-tools>adb shell


BusyBox v1.27.2 () built-in shell (ash)

 _____  _              __     _
|_   _||_| ___  _ _   |  |   |_| ___  _ _  _ _
  | |   _ |   ||   |  |  |__ | ||   || | ||_'_|
  | |  | || | || _ |  |_____||_||_|_||___||_,_|
  |_|  |_||_|_||_|_|  Tina is Based on OpenWrt!
 ----------------------------------------------
 Tina Linux (Neptune, 5C1C9C53)
 ----------------------------------------------
root@TinaLinux:/# cd /mnt/SDCARD
cd /mnt/SDCARD
root@TinaLinux:/mnt/SDCARD# ls
ls
Apps                       Saves
Best                       System Volume Information
Emus                       Themes
Imgs                       Videos
Ports                      adb
RetroArch                  evtest
Roms
root@TinaLinux:/mnt/SDCARD# ./evtest
./evtest
No device specified, trying to scan all of /dev/input/event*
Available devices:
/dev/input/event0:      sunxi-keyboard
/dev/input/event1:      axp2202-pek
/dev/input/event2:      audiocodec sunxi Audio Jack
/dev/input/event3:      TRIMUI Player1
Select the device event number [0-3]: 0
0
Input driver version is 1.0.1
Input device ID: bus 0x19 vendor 0x1 product 0x1 version 0x100
Input device name: "sunxi-keyboard"
Supported events:
  Event type 0 (EV_SYN)
  Event type 1 (EV_KEY)
    Event code 114 (KEY_VOLUMEDOWN)
    Event code 115 (KEY_VOLUMEUP)
Properties:
Testing ... (interrupt to exit)
^C
D:\adt-bundle-windows-x86-20140624\sdk\platform-tools>adb shell


BusyBox v1.27.2 () built-in shell (ash)

 _____  _              __     _
|_   _||_| ___  _ _   |  |   |_| ___  _ _  _ _
  | |   _ |   ||   |  |  |__ | ||   || | ||_'_|
  | |  | || | || _ |  |_____||_||_|_||___||_,_|
  |_|  |_||_|_||_|_|  Tina is Based on OpenWrt!
 ----------------------------------------------
 Tina Linux (Neptune, 5C1C9C53)
 ----------------------------------------------
root@TinaLinux:/# /mnt/SDCARD/evtest
/mnt/SDCARD/evtest
No device specified, trying to scan all of /dev/input/event*
Available devices:
/dev/input/event0:      sunxi-keyboard
/dev/input/event1:      axp2202-pek
/dev/input/event2:      audiocodec sunxi Audio Jack
/dev/input/event3:      TRIMUI Player1
Select the device event number [0-3]: 3
3
Input driver version is 1.0.1
Input device ID: bus 0x3 vendor 0x45e product 0x28e version 0x114
Input device name: "TRIMUI Player1"
Supported events:
  Event type 0 (EV_SYN)
  Event type 1 (EV_KEY)
    Event code 59 (KEY_F1)
    Event code 60 (KEY_F2)
    Event code 114 (KEY_VOLUMEDOWN)
    Event code 115 (KEY_VOLUMEUP)
    Event code 304 (BTN_SOUTH)
    Event code 305 (BTN_EAST)
    Event code 307 (BTN_NORTH)
    Event code 308 (BTN_WEST)
    Event code 310 (BTN_TL)
    Event code 311 (BTN_TR)
    Event code 314 (BTN_SELECT)
    Event code 315 (BTN_START)
    Event code 316 (BTN_MODE)
    Event code 317 (BTN_THUMBL)
    Event code 318 (BTN_THUMBR)
  Event type 3 (EV_ABS)
    Event code 0 (ABS_X)
      Value      0
      Min   -32767
      Max    32767
    Event code 1 (ABS_Y)
      Value      0
      Min   -32767
      Max    32767
    Event code 2 (ABS_Z)
      Value      0
      Min        0
      Max      255
    Event code 3 (ABS_RX)
      Value      0
      Min   -32767
      Max    32767
    Event code 4 (ABS_RY)
      Value      0
      Min   -32767
      Max    32767
    Event code 5 (ABS_RZ)
      Value      0
      Min        0
      Max      255
    Event code 16 (ABS_HAT0X)
      Value      0
      Min       -1
      Max        1
    Event code 17 (ABS_HAT0Y)
      Value      0
      Min       -1
      Max        1
  Event type 5 (EV_SW)
    Event code 1 (SW_TABLET_MODE)
Properties:
Testing ... (interrupt to exit)
Event: time 1732342182.388469, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342182.388469, -------------- SYN_REPORT ------------
Event: time 1732342182.574980, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342182.574980, -------------- SYN_REPORT ------------
Event: time 1732342183.506247, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342183.506247, -------------- SYN_REPORT ------------
Event: time 1732342183.607927, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342183.607927, -------------- SYN_REPORT ------------
Event: time 1732342184.192326, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value -1
Event: time 1732342184.192326, -------------- SYN_REPORT ------------
Event: time 1732342184.327900, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342184.327900, -------------- SYN_REPORT ------------
Event: time 1732342184.810142, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342184.810142, -------------- SYN_REPORT ------------
Event: time 1732342184.928702, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342184.928702, -------------- SYN_REPORT ------------
Event: time 1732342186.901430, type 1 (EV_KEY), code 316 (BTN_MODE), value 1
Event: time 1732342186.901430, -------------- SYN_REPORT ------------
Event: time 1732342187.053815, type 1 (EV_KEY), code 316 (BTN_MODE), value 0
Event: time 1732342187.053815, -------------- SYN_REPORT ------------
Event: time 1732342188.331435, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 1
Event: time 1732342188.331435, -------------- SYN_REPORT ------------
Event: time 1732342188.500624, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 0
Event: time 1732342188.500624, -------------- SYN_REPORT ------------
Event: time 1732342189.247457, type 1 (EV_KEY), code 314 (BTN_SELECT), value 1
Event: time 1732342189.247457, -------------- SYN_REPORT ------------
Event: time 1732342189.383334, type 1 (EV_KEY), code 314 (BTN_SELECT), value 0
Event: time 1732342189.383334, -------------- SYN_REPORT ------------
Event: time 1732342190.265821, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 1
Event: time 1732342190.265821, -------------- SYN_REPORT ------------
Event: time 1732342190.410121, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 0
Event: time 1732342190.410121, -------------- SYN_REPORT ------------
Event: time 1732342191.020986, type 1 (EV_KEY), code 315 (BTN_START), value 1
Event: time 1732342191.020986, -------------- SYN_REPORT ------------
Event: time 1732342191.182503, type 1 (EV_KEY), code 315 (BTN_START), value 0
Event: time 1732342191.182503, -------------- SYN_REPORT ------------
Event: time 1732342192.074861, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 1
Event: time 1732342192.074861, -------------- SYN_REPORT ------------
Event: time 1732342192.235789, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 0
Event: time 1732342192.235789, -------------- SYN_REPORT ------------
Event: time 1732342193.064721, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 1
Event: time 1732342193.064721, -------------- SYN_REPORT ------------
Event: time 1732342193.225180, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 0
Event: time 1732342193.225180, -------------- SYN_REPORT ------------
Event: time 1732342194.698228, type 1 (EV_KEY), code 315 (BTN_START), value 1
Event: time 1732342194.698228, -------------- SYN_REPORT ------------
Event: time 1732342194.842383, type 1 (EV_KEY), code 315 (BTN_START), value 0
Event: time 1732342194.842383, -------------- SYN_REPORT ------------
Event: time 1732342196.112440, type 1 (EV_KEY), code 315 (BTN_START), value 1
Event: time 1732342196.112440, -------------- SYN_REPORT ------------
Event: time 1732342196.239433, type 1 (EV_KEY), code 315 (BTN_START), value 0
Event: time 1732342196.239433, -------------- SYN_REPORT ------------
Event: time 1732342196.958682, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 1
Event: time 1732342196.958682, -------------- SYN_REPORT ------------
Event: time 1732342197.162065, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 0
Event: time 1732342197.162065, -------------- SYN_REPORT ------------
Event: time 1732342199.411915, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342199.411915, -------------- SYN_REPORT ------------
Event: time 1732342199.505015, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342199.505015, -------------- SYN_REPORT ------------
Event: time 1732342199.641082, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342199.641082, -------------- SYN_REPORT ------------
Event: time 1732342199.725807, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342199.725807, -------------- SYN_REPORT ------------
Event: time 1732342200.013643, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342200.013643, -------------- SYN_REPORT ------------
Event: time 1732342200.115337, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342200.115337, -------------- SYN_REPORT ------------
Event: time 1732342200.834943, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342200.834943, -------------- SYN_REPORT ------------
Event: time 1732342200.936782, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342200.936782, -------------- SYN_REPORT ------------
Event: time 1732342201.574122, type 1 (EV_KEY), code 315 (BTN_START), value 1
Event: time 1732342201.574122, -------------- SYN_REPORT ------------
Event: time 1732342201.743719, type 1 (EV_KEY), code 315 (BTN_START), value 0
Event: time 1732342201.743719, -------------- SYN_REPORT ------------
Event: time 1732342203.348180, type 1 (EV_KEY), code 315 (BTN_START), value 1
Event: time 1732342203.348180, -------------- SYN_REPORT ------------
Event: time 1732342203.509274, type 1 (EV_KEY), code 315 (BTN_START), value 0
Event: time 1732342203.509274, -------------- SYN_REPORT ------------
Event: time 1732342206.316856, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value -1
Event: time 1732342206.316856, -------------- SYN_REPORT ------------
Event: time 1732342206.477512, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342206.477512, -------------- SYN_REPORT ------------
Event: time 1732342206.883601, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342206.883601, -------------- SYN_REPORT ------------
Event: time 1732342206.985123, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342206.985123, -------------- SYN_REPORT ------------
Event: time 1732342207.391713, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342207.391713, -------------- SYN_REPORT ------------
Event: time 1732342207.484775, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342207.484775, -------------- SYN_REPORT ------------
Event: time 1732342207.823177, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342207.823177, -------------- SYN_REPORT ------------
Event: time 1732342207.924670, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342207.924670, -------------- SYN_REPORT ------------
Event: time 1732342208.263844, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342208.263844, -------------- SYN_REPORT ------------
Event: time 1732342208.374323, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342208.374323, -------------- SYN_REPORT ------------
Event: time 1732342209.204767, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342209.204767, -------------- SYN_REPORT ------------
Event: time 1732342209.314993, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342209.314993, -------------- SYN_REPORT ------------
Event: time 1732342209.458953, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342209.458953, -------------- SYN_REPORT ------------
Event: time 1732342209.569689, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342209.569689, -------------- SYN_REPORT ------------
Event: time 1732342209.688209, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342209.688209, -------------- SYN_REPORT ------------
Event: time 1732342209.773387, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342209.773387, -------------- SYN_REPORT ------------
Event: time 1732342210.120782, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342210.120782, -------------- SYN_REPORT ------------
Event: time 1732342210.256761, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342210.256761, -------------- SYN_REPORT ------------
Event: time 1732342210.409093, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342210.409093, -------------- SYN_REPORT ------------
Event: time 1732342210.511021, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342210.511021, -------------- SYN_REPORT ------------
Event: time 1732342210.629806, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342210.629806, -------------- SYN_REPORT ------------
Event: time 1732342210.748879, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342210.748879, -------------- SYN_REPORT ------------
Event: time 1732342210.850575, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342210.850575, -------------- SYN_REPORT ------------
Event: time 1732342210.960945, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342210.960945, -------------- SYN_REPORT ------------
Event: time 1732342211.392827, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342211.392827, -------------- SYN_REPORT ------------
Event: time 1732342211.502906, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342211.502906, -------------- SYN_REPORT ------------
Event: time 1732342211.765001, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342211.765001, -------------- SYN_REPORT ------------
Event: time 1732342211.942995, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342211.942995, -------------- SYN_REPORT ------------
Event: time 1732342212.391296, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342212.391296, -------------- SYN_REPORT ------------
Event: time 1732342212.501404, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342212.501404, -------------- SYN_REPORT ------------
Event: time 1732342212.586143, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342212.586143, -------------- SYN_REPORT ------------
Event: time 1732342212.696146, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342212.696146, -------------- SYN_REPORT ------------
Event: time 1732342212.797684, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342212.797684, -------------- SYN_REPORT ------------
Event: time 1732342212.899252, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342212.899252, -------------- SYN_REPORT ------------
Event: time 1732342213.000932, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342213.000932, -------------- SYN_REPORT ------------
Event: time 1732342213.085634, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342213.085634, -------------- SYN_REPORT ------------
Event: time 1732342213.195642, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342213.195642, -------------- SYN_REPORT ------------
Event: time 1732342213.305620, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342213.305620, -------------- SYN_REPORT ------------
Event: time 1732342213.398678, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342213.398678, -------------- SYN_REPORT ------------
Event: time 1732342213.492060, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342213.492060, -------------- SYN_REPORT ------------
Event: time 1732342213.618938, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342213.618938, -------------- SYN_REPORT ------------
Event: time 1732342213.712017, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342213.712017, -------------- SYN_REPORT ------------
Event: time 1732342213.830423, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342213.830423, -------------- SYN_REPORT ------------
Event: time 1732342213.965885, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342213.965885, -------------- SYN_REPORT ------------
Event: time 1732342214.059150, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342214.059150, -------------- SYN_REPORT ------------
Event: time 1732342214.169225, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342214.169225, -------------- SYN_REPORT ------------
Event: time 1732342214.279274, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342214.279274, -------------- SYN_REPORT ------------
Event: time 1732342214.431445, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342214.431445, -------------- SYN_REPORT ------------
Event: time 1732342216.208077, type 1 (EV_KEY), code 310 (BTN_TL), value 1
Event: time 1732342216.208077, -------------- SYN_REPORT ------------
Event: time 1732342216.385800, type 1 (EV_KEY), code 310 (BTN_TL), value 0
Event: time 1732342216.385800, -------------- SYN_REPORT ------------
Event: time 1732342217.079480, type 1 (EV_KEY), code 311 (BTN_TR), value 1
Event: time 1732342217.079480, -------------- SYN_REPORT ------------
Event: time 1732342217.341813, type 1 (EV_KEY), code 311 (BTN_TR), value 0
Event: time 1732342217.341813, -------------- SYN_REPORT ------------
Event: time 1732342217.587024, type 1 (EV_KEY), code 311 (BTN_TR), value 1
Event: time 1732342217.587024, -------------- SYN_REPORT ------------
Event: time 1732342217.748017, type 1 (EV_KEY), code 311 (BTN_TR), value 0
Event: time 1732342217.748017, -------------- SYN_REPORT ------------
Event: time 1732342217.976526, type 1 (EV_KEY), code 311 (BTN_TR), value 1
Event: time 1732342217.976526, -------------- SYN_REPORT ------------
Event: time 1732342218.154147, type 1 (EV_KEY), code 311 (BTN_TR), value 0
Event: time 1732342218.154147, -------------- SYN_REPORT ------------
Event: time 1732342218.839097, type 3 (EV_ABS), code 2 (ABS_Z), value 255
Event: time 1732342218.839097, -------------- SYN_REPORT ------------
Event: time 1732342219.016831, type 3 (EV_ABS), code 2 (ABS_Z), value 0
Event: time 1732342219.016831, -------------- SYN_REPORT ------------
Event: time 1732342219.287358, type 3 (EV_ABS), code 2 (ABS_Z), value 255
Event: time 1732342219.287358, -------------- SYN_REPORT ------------
Event: time 1732342219.456616, type 3 (EV_ABS), code 2 (ABS_Z), value 0
Event: time 1732342219.456616, -------------- SYN_REPORT ------------
Event: time 1732342219.524261, type 3 (EV_ABS), code 5 (ABS_RZ), value 255
Event: time 1732342219.524261, -------------- SYN_REPORT ------------
Event: time 1732342219.752872, type 3 (EV_ABS), code 5 (ABS_RZ), value 0
Event: time 1732342219.752872, -------------- SYN_REPORT ------------
Event: time 1732342219.829150, type 3 (EV_ABS), code 5 (ABS_RZ), value 255
Event: time 1732342219.829150, -------------- SYN_REPORT ------------
Event: time 1732342220.006770, type 3 (EV_ABS), code 5 (ABS_RZ), value 0
Event: time 1732342220.006770, -------------- SYN_REPORT ------------
Event: time 1732342220.421554, type 3 (EV_ABS), code 2 (ABS_Z), value 255
Event: time 1732342220.421554, -------------- SYN_REPORT ------------
Event: time 1732342220.565375, type 3 (EV_ABS), code 2 (ABS_Z), value 0
Event: time 1732342220.565375, -------------- SYN_REPORT ------------
Event: time 1732342220.734490, type 3 (EV_ABS), code 2 (ABS_Z), value 255
Event: time 1732342220.734490, -------------- SYN_REPORT ------------
Event: time 1732342220.878637, type 3 (EV_ABS), code 2 (ABS_Z), value 0
Event: time 1732342220.878637, -------------- SYN_REPORT ------------
Event: time 1732342221.090019, type 3 (EV_ABS), code 5 (ABS_RZ), value 255
Event: time 1732342221.090019, -------------- SYN_REPORT ------------
Event: time 1732342221.276208, type 3 (EV_ABS), code 5 (ABS_RZ), value 0
Event: time 1732342221.276208, -------------- SYN_REPORT ------------
Event: time 1732342221.428616, type 3 (EV_ABS), code 5 (ABS_RZ), value 255
Event: time 1732342221.428616, -------------- SYN_REPORT ------------
Event: time 1732342221.597738, type 3 (EV_ABS), code 5 (ABS_RZ), value 0
Event: time 1732342221.597738, -------------- SYN_REPORT ------------
Event: time 1732342222.570213, type 1 (EV_KEY), code 310 (BTN_TL), value 1
Event: time 1732342222.570213, -------------- SYN_REPORT ------------
Event: time 1732342222.747983, type 1 (EV_KEY), code 310 (BTN_TL), value 0
Event: time 1732342222.747983, -------------- SYN_REPORT ------------
Event: time 1732342222.984745, type 1 (EV_KEY), code 310 (BTN_TL), value 1
Event: time 1732342222.984745, -------------- SYN_REPORT ------------
Event: time 1732342223.120167, type 1 (EV_KEY), code 310 (BTN_TL), value 0
Event: time 1732342223.120167, -------------- SYN_REPORT ------------
Event: time 1732342223.373884, type 1 (EV_KEY), code 311 (BTN_TR), value 1
Event: time 1732342223.373884, -------------- SYN_REPORT ------------
Event: time 1732342223.568595, type 1 (EV_KEY), code 311 (BTN_TR), value 0
Event: time 1732342223.568595, -------------- SYN_REPORT ------------
Event: time 1732342223.754814, type 1 (EV_KEY), code 311 (BTN_TR), value 1
Event: time 1732342223.754814, -------------- SYN_REPORT ------------
Event: time 1732342223.923922, type 1 (EV_KEY), code 311 (BTN_TR), value 0
Event: time 1732342223.923922, -------------- SYN_REPORT ------------
Event: time 1732342226.790323, type 1 (EV_KEY), code 115 (KEY_VOLUMEUP), value 1
Event: time 1732342226.790323, -------------- SYN_REPORT ------------
Event: time 1732342227.010591, type 1 (EV_KEY), code 115 (KEY_VOLUMEUP), value 0
Event: time 1732342227.010591, -------------- SYN_REPORT ------------
Event: time 1732342227.230570, type 1 (EV_KEY), code 115 (KEY_VOLUMEUP), value 1
Event: time 1732342227.230570, -------------- SYN_REPORT ------------
Event: time 1732342227.391559, type 1 (EV_KEY), code 115 (KEY_VOLUMEUP), value 0
Event: time 1732342227.391559, -------------- SYN_REPORT ------------
Event: time 1732342228.313512, type 1 (EV_KEY), code 114 (KEY_VOLUMEDOWN), value 1
Event: time 1732342228.313512, -------------- SYN_REPORT ------------
Event: time 1732342228.516640, type 1 (EV_KEY), code 114 (KEY_VOLUMEDOWN), value 0
Event: time 1732342228.516640, -------------- SYN_REPORT ------------
Event: time 1732342228.694574, type 1 (EV_KEY), code 114 (KEY_VOLUMEDOWN), value 1
Event: time 1732342228.694574, -------------- SYN_REPORT ------------
Event: time 1732342228.863833, type 1 (EV_KEY), code 114 (KEY_VOLUMEDOWN), value 0
Event: time 1732342228.863833, -------------- SYN_REPORT ------------
Event: time 1732342233.423225, type 5 (EV_SW), code 1 (SW_TABLET_MODE), value 0
Event: time 1732342233.423225, -------------- SYN_REPORT ------------
Event: time 1732342235.425484, type 5 (EV_SW), code 1 (SW_TABLET_MODE), value 1
Event: time 1732342235.425484, -------------- SYN_REPORT ------------
Event: time 1732342237.427674, type 5 (EV_SW), code 1 (SW_TABLET_MODE), value 0
Event: time 1732342237.427674, -------------- SYN_REPORT ------------
Event: time 1732342239.429821, type 5 (EV_SW), code 1 (SW_TABLET_MODE), value 1
Event: time 1732342239.429821, -------------- SYN_REPORT ------------
Event: time 1732342241.432056, type 5 (EV_SW), code 1 (SW_TABLET_MODE), value 0
Event: time 1732342241.432056, -------------- SYN_REPORT ------------
Event: time 1732342242.433225, type 5 (EV_SW), code 1 (SW_TABLET_MODE), value 1
Event: time 1732342242.433225, -------------- SYN_REPORT ------------
Event: time 1732342254.214802, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 1
Event: time 1732342254.214802, -------------- SYN_REPORT ------------
Event: time 1732342254.417808, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 0
Event: time 1732342254.417808, -------------- SYN_REPORT ------------
Event: time 1732342257.322048, type 1 (EV_KEY), code 305 (BTN_EAST), value 1
Event: time 1732342257.322048, -------------- SYN_REPORT ------------
Event: time 1732342257.466205, type 1 (EV_KEY), code 305 (BTN_EAST), value 0
Event: time 1732342257.466205, -------------- SYN_REPORT ------------
Event: time 1732342258.448462, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 1
Event: time 1732342258.448462, -------------- SYN_REPORT ------------
Event: time 1732342258.626287, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 0
Event: time 1732342258.626287, -------------- SYN_REPORT ------------
Event: time 1732342259.924437, type 1 (EV_KEY), code 305 (BTN_EAST), value 1
Event: time 1732342259.924437, -------------- SYN_REPORT ------------
Event: time 1732342260.077125, type 1 (EV_KEY), code 305 (BTN_EAST), value 0
Event: time 1732342260.077125, -------------- SYN_REPORT ------------
Event: time 1732342261.342443, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 1
Event: time 1732342261.342443, -------------- SYN_REPORT ------------
Event: time 1732342261.520963, type 1 (EV_KEY), code 304 (BTN_SOUTH), value 0
Event: time 1732342261.520963, -------------- SYN_REPORT ------------
Event: time 1732342264.349165, type 1 (EV_KEY), code 307 (BTN_NORTH), value 1
Event: time 1732342264.349165, -------------- SYN_REPORT ------------
Event: time 1732342264.518927, type 1 (EV_KEY), code 307 (BTN_NORTH), value 0
Event: time 1732342264.518927, -------------- SYN_REPORT ------------
Event: time 1732342265.516442, type 1 (EV_KEY), code 307 (BTN_NORTH), value 1
Event: time 1732342265.516442, -------------- SYN_REPORT ------------
Event: time 1732342265.719558, type 1 (EV_KEY), code 307 (BTN_NORTH), value 0
Event: time 1732342265.719558, -------------- SYN_REPORT ------------
Event: time 1732342266.015575, type 1 (EV_KEY), code 307 (BTN_NORTH), value 1
Event: time 1732342266.015575, -------------- SYN_REPORT ------------
Event: time 1732342266.134360, type 1 (EV_KEY), code 307 (BTN_NORTH), value 0
Event: time 1732342266.134360, -------------- SYN_REPORT ------------
Event: time 1732342266.329143, type 1 (EV_KEY), code 307 (BTN_NORTH), value 1
Event: time 1732342266.329143, -------------- SYN_REPORT ------------
Event: time 1732342266.464508, type 1 (EV_KEY), code 307 (BTN_NORTH), value 0
Event: time 1732342266.464508, -------------- SYN_REPORT ------------
Event: time 1732342266.532268, type 1 (EV_KEY), code 307 (BTN_NORTH), value 1
Event: time 1732342266.532268, -------------- SYN_REPORT ------------
Event: time 1732342266.684614, type 1 (EV_KEY), code 307 (BTN_NORTH), value 0
Event: time 1732342266.684614, -------------- SYN_REPORT ------------
Event: time 1732342267.090959, type 1 (EV_KEY), code 308 (BTN_WEST), value 1
Event: time 1732342267.090959, -------------- SYN_REPORT ------------
Event: time 1732342267.235055, type 1 (EV_KEY), code 308 (BTN_WEST), value 0
Event: time 1732342267.235055, -------------- SYN_REPORT ------------
Event: time 1732342267.624041, type 1 (EV_KEY), code 308 (BTN_WEST), value 1
Event: time 1732342267.624041, -------------- SYN_REPORT ------------
Event: time 1732342267.767870, type 1 (EV_KEY), code 308 (BTN_WEST), value 0
Event: time 1732342267.767870, -------------- SYN_REPORT ------------
Event: time 1732342267.886496, type 1 (EV_KEY), code 308 (BTN_WEST), value 1
Event: time 1732342267.886496, -------------- SYN_REPORT ------------
Event: time 1732342268.250368, type 1 (EV_KEY), code 308 (BTN_WEST), value 0
Event: time 1732342268.250368, -------------- SYN_REPORT ------------
Event: time 1732342268.360503, type 1 (EV_KEY), code 308 (BTN_WEST), value 1
Event: time 1732342268.360503, -------------- SYN_REPORT ------------
Event: time 1732342268.495977, type 1 (EV_KEY), code 308 (BTN_WEST), value 0
Event: time 1732342268.495977, -------------- SYN_REPORT ------------
Event: time 1732342268.614439, type 1 (EV_KEY), code 308 (BTN_WEST), value 1
Event: time 1732342268.614439, -------------- SYN_REPORT ------------
Event: time 1732342268.715987, type 1 (EV_KEY), code 308 (BTN_WEST), value 0
Event: time 1732342268.715987, -------------- SYN_REPORT ------------
Event: time 1732342268.826004, type 1 (EV_KEY), code 308 (BTN_WEST), value 1
Event: time 1732342268.826004, -------------- SYN_REPORT ------------
Event: time 1732342268.902201, type 1 (EV_KEY), code 308 (BTN_WEST), value 0
Event: time 1732342268.902201, -------------- SYN_REPORT ------------
Event: time 1732342269.283342, type 1 (EV_KEY), code 308 (BTN_WEST), value 1
Event: time 1732342269.283342, -------------- SYN_REPORT ------------
Event: time 1732342269.427184, type 1 (EV_KEY), code 308 (BTN_WEST), value 0
Event: time 1732342269.427184, -------------- SYN_REPORT ------------
Event: time 1732342269.706732, type 1 (EV_KEY), code 308 (BTN_WEST), value 1
Event: time 1732342269.706732, -------------- SYN_REPORT ------------
Event: time 1732342269.867505, type 1 (EV_KEY), code 308 (BTN_WEST), value 0
Event: time 1732342269.867505, -------------- SYN_REPORT ------------
Event: time 1732342270.163906, type 1 (EV_KEY), code 307 (BTN_NORTH), value 1
Event: time 1732342270.163906, -------------- SYN_REPORT ------------
Event: time 1732342270.350018, type 1 (EV_KEY), code 307 (BTN_NORTH), value 0
Event: time 1732342270.350018, -------------- SYN_REPORT ------------
Event: time 1732342271.720698, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342271.720698, -------------- SYN_REPORT ------------
Event: time 1732342271.898533, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342271.898533, -------------- SYN_REPORT ------------
Event: time 1732342272.287801, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342272.287801, -------------- SYN_REPORT ------------
Event: time 1732342272.440438, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342272.440438, -------------- SYN_REPORT ------------
Event: time 1732342272.829690, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342272.829690, -------------- SYN_REPORT ------------
Event: time 1732342272.965373, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342272.965373, -------------- SYN_REPORT ------------
Event: time 1732342273.143335, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 1
Event: time 1732342273.143335, -------------- SYN_REPORT ------------
Event: time 1732342273.279368, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342273.279368, -------------- SYN_REPORT ------------
Event: time 1732342273.999747, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342273.999747, -------------- SYN_REPORT ------------
Event: time 1732342274.177575, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342274.177575, -------------- SYN_REPORT ------------
Event: time 1732342274.330659, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342274.330659, -------------- SYN_REPORT ------------
Event: time 1732342274.440841, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342274.440841, -------------- SYN_REPORT ------------
Event: time 1732342274.542481, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342274.542481, -------------- SYN_REPORT ------------
Event: time 1732342274.678416, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342274.678416, -------------- SYN_REPORT ------------
Event: time 1732342274.780040, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342274.780040, -------------- SYN_REPORT ------------
Event: time 1732342274.941259, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342274.941259, -------------- SYN_REPORT ------------
Event: time 1732342275.043171, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342275.043171, -------------- SYN_REPORT ------------
Event: time 1732342275.187203, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342275.187203, -------------- SYN_REPORT ------------
Event: time 1732342275.289254, type 3 (EV_ABS), code 16 (ABS_HAT0X), value -1
Event: time 1732342275.289254, -------------- SYN_REPORT ------------
Event: time 1732342275.416286, type 3 (EV_ABS), code 16 (ABS_HAT0X), value 0
Event: time 1732342275.416286, -------------- SYN_REPORT ------------
Event: time 1732342275.865589, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value -1
Event: time 1732342275.865589, -------------- SYN_REPORT ------------
Event: time 1732342276.052112, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342276.052112, -------------- SYN_REPORT ------------
Event: time 1732342276.179325, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value -1
Event: time 1732342276.179325, -------------- SYN_REPORT ------------
Event: time 1732342276.315352, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342276.315352, -------------- SYN_REPORT ------------
Event: time 1732342276.442384, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value -1
Event: time 1732342276.442384, -------------- SYN_REPORT ------------
Event: time 1732342276.595175, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342276.595175, -------------- SYN_REPORT ------------
Event: time 1732342276.722154, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value -1
Event: time 1732342276.722154, -------------- SYN_REPORT ------------
Event: time 1732342276.857620, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342276.857620, -------------- SYN_REPORT ------------
Event: time 1732342277.509016, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342277.509016, -------------- SYN_REPORT ------------
Event: time 1732342277.602250, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342277.602250, -------------- SYN_REPORT ------------
Event: time 1732342277.788567, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342277.788567, -------------- SYN_REPORT ------------
Event: time 1732342277.941372, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342277.941372, -------------- SYN_REPORT ------------
Event: time 1732342278.094264, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342278.094264, -------------- SYN_REPORT ------------
Event: time 1732342278.247024, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342278.247024, -------------- SYN_REPORT ------------
Event: time 1732342278.357467, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342278.357467, -------------- SYN_REPORT ------------
Event: time 1732342278.484748, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342278.484748, -------------- SYN_REPORT ------------
Event: time 1732342278.671519, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342278.671519, -------------- SYN_REPORT ------------
Event: time 1732342278.824348, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342278.824348, -------------- SYN_REPORT ------------
Event: time 1732342279.002818, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342279.002818, -------------- SYN_REPORT ------------
Event: time 1732342279.147563, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342279.147563, -------------- SYN_REPORT ------------
Event: time 1732342279.292129, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342279.292129, -------------- SYN_REPORT ------------
Event: time 1732342279.428036, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342279.428036, -------------- SYN_REPORT ------------
Event: time 1732342279.572226, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342279.572226, -------------- SYN_REPORT ------------
Event: time 1732342279.699511, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342279.699511, -------------- SYN_REPORT ------------
Event: time 1732342279.776430, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342279.776430, -------------- SYN_REPORT ------------
Event: time 1732342279.903824, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342279.903824, -------------- SYN_REPORT ------------
Event: time 1732342279.988572, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342279.988572, -------------- SYN_REPORT ------------
Event: time 1732342280.107450, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342280.107450, -------------- SYN_REPORT ------------
Event: time 1732342280.158520, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342280.158520, -------------- SYN_REPORT ------------
Event: time 1732342280.446994, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342280.446994, -------------- SYN_REPORT ------------
Event: time 1732342280.531785, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342280.531785, -------------- SYN_REPORT ------------
Event: time 1732342280.684295, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342280.684295, -------------- SYN_REPORT ------------
Event: time 1732342280.803411, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 1
Event: time 1732342280.803411, -------------- SYN_REPORT ------------
Event: time 1732342280.913833, type 3 (EV_ABS), code 17 (ABS_HAT0Y), value 0
Event: time 1732342280.913833, -------------- SYN_REPORT ------------

