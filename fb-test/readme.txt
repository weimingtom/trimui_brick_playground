killall -KILL runtrimui.sh MainUI

-----


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

D:\adt-bundle-windows-x86-20140624\sdk\platform-tools>adb push rect /mnt/SDCARD/
1109 KB/s (18856 bytes in 0.016s)

D:\adt-bundle-windows-x86-20140624\sdk\platform-tools>adb push fb-test /mnt/SDCARD/
1238 KB/s (21056 bytes in 0.016s)

D:\adt-bundle-windows-x86-20140624\sdk\platform-tools>adb push offset /mnt/SDCARD/
895 KB/s (14448 bytes in 0.015s)

D:\adt-bundle-windows-x86-20140624\sdk\platform-tools>adb push perf /mnt/SDCARD/
1306 KB/s (19584 bytes in 0.014s)

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
Apps                       adb
Best                       evtest
Emus                       fb-test
Imgs                       graywin
Ports                      icon.bmp
RetroArch                  lvgl_demo
Roms                       offset
Saves                      perf
System Volume Information  rect
Themes                     test.elf
Videos
root@TinaLinux:/mnt/SDCARD# killall -KILL runtrimui.sh MainUI
killall -KILL runtrimui.sh MainUI
root@TinaLinux:/mnt/SDCARD# fb-test
fb-test
/bin/sh: fb-test: not found
root@TinaLinux:/mnt/SDCARD# ./fb-test
./fb-test
fb-test 1.0.0 (tablet_rosa)
fb res 1024x768 virtual 1024x16384, line_len 4096
dim 135mm x 216mm
root@TinaLinux:/mnt/SDCARD#
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
root@TinaLinux:/# fb-test
fb-test
/bin/sh: fb-test: not found
root@TinaLinux:/# cd /mnt/SDCARD
cd /mnt/SDCARD
root@TinaLinux:/mnt/SDCARD# ./fb-test
./fb-test
fb-test 1.0.0 (tablet_rosa)
fb res 1024x768 virtual 1024x16384, line_len 4096
dim 135mm x 216mm
root@TinaLinux:/mnt/SDCARD# ./rect
./rect
rect 1.0.0 (tablet_rosa)
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
root@TinaLinux:/# ./perf
./perf
/bin/sh: ./perf: not found
root@TinaLinux:/# cd /mnt/SDCARD
cd /mnt/SDCARD
root@TinaLinux:/mnt/SDCARD# ./perf
./perf
perf 1.0.0 (tablet_rosa)
usage: ./perf <fbnum> <logfile>
root@TinaLinux:/mnt/SDCARD# ./perf 0
./perf 0
perf 1.0.0 (tablet_rosa)
usage: ./perf <fbnum> <logfile>
root@TinaLinux:/mnt/SDCARD# ./perf 0 a.txt
./perf 0 a.txt
perf 1.0.0 (tablet_rosa)
sequential_horiz_singlepixel_read: cat a.txt
cat a.txt
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
root@TinaLinux:/# ls
ls
bin         lib64       overlay     root        usr
dev         lost+found  proc        sbin        var
etc         mnt         rdinit      sys         www
lib         mono        rom         tmp
root@TinaLinux:/# cd /mnt/SDCARD
cd /mnt/SDCARD
root@TinaLinux:/mnt/SDCARD# ls
ls
Apps                       a.txt
Best                       adb
Emus                       evtest
Imgs                       fb-test
Ports                      graywin
RetroArch                  icon.bmp
Roms                       lvgl_demo
Saves                      offset
System Volume Information  perf
Themes                     rect
Videos                     test.elf
root@TinaLinux:/mnt/SDCARD# ls -al
ls -al
drwxrwxrwx   14 root     root         32768 Nov 24 14:58 .
drwxr-xr-x    1 root     root          4096 Nov 23 12:55 ..
drwxrwxrwx    3 root     root         32768 Nov 12 01:20 .config
drwxrwxrwx   11 root     root         32768 Nov 12 01:20 Apps
drwxrwxrwx    5 root     root         32768 Nov 12 01:20 Best
drwxrwxrwx   40 root     root         32768 Nov 12 01:21 Emus
drwxrwxrwx   39 root     root         32768 Nov 12 01:23 Imgs
drwxrwxrwx   11 root     root         32768 Nov 12 01:24 Ports
drwxrwxrwx    3 root     root         32768 Nov 12 01:25 RetroArch
drwxrwxrwx   39 root     root         32768 Nov 21 19:11 Roms
drwxrwxrwx    3 root     root         32768 Nov 20 05:36 Saves
drwxrwxrwx    2 root     root         32768 Nov 14 23:51 System Volume Information
drwxrwxrwx    6 root     root         32768 Nov 12 01:49 Themes
drwxrwxrwx    2 root     root         32768 Nov 12 01:49 Videos
-rwxrwxrwx    1 root     root             0 Nov 24 14:58 a.txt
-rwxrwxrwx    1 root     root             0 Nov 23 12:12 adb
-rwxrwxrwx    1 root     root         49824 Nov 23 14:06 evtest
-rwxrwxrwx    1 root     root         21056 Nov 24 14:50 fb-test
-rwxrwxrwx    1 root     root       1159184 Nov 23 14:55 graywin
-rwxrwxrwx    1 root     root           578 Nov 23 14:55 icon.bmp
-rwxrwxrwx    1 root     root       8453704 Nov 23 15:21 lvgl_demo
-rwxrwxrwx    1 root     root         14448 Nov 24 14:50 offset
-rwxrwxrwx    1 root     root         19584 Nov 24 14:50 perf
-rwxrwxrwx    1 root     root         18856 Nov 24 14:51 rect
-rwxrwxrwx    1 root     root        100096 Nov 23 14:21 test.elf
root@TinaLinux:/mnt/SDCARD# ./offset
./offset
offset 1.0.0 (tablet_rosa)
usage: ./offset [-f <fbnum>] <x> <y>
root@TinaLinux:/mnt/SDCARD# ./offset -f 0 0 0
./offset -f 0 0 0
offset 1.0.0 (tablet_rosa)
root@TinaLinux:/mnt/SDCARD# ./offset -f fb0 0 0
./offset -f fb0 0 0
offset 1.0.0 (tablet_rosa)
root@TinaLinux:/mnt/SDCARD#

