# trimui_brick_playground
My TRIMUI BRICK playground

## Toolchain  
* aarch64-linux-gnu-7.5.0-linaro.tgz  
* SDK_usr_tg5040_a133p.tgz  

## /adb
* if exists /adb, delete this file to avoid adb shell failed  

## killall -KILL runtrimui.sh MainUI  
* killall -KILL runtrimui.sh MainUI   
```
killall -KILL runtrimui.sh MainUI  
ls /dev/fb*
cat /dev/zero > /dev/fb0  
cat /dev/urandom > /dev/fb0  
root@TinaLinux:/# fbset
fbset

mode "1024x768-60"
        # D: 53.003 MHz, H: 48.184 kHz, V: 60.230 Hz
        geometry 1024 768 1024 16384 32
        timings 18867 16 56 5 23 4 4
        accel false
        rgba 8/16,8/8,8/0,8/24
endmode

root@TinaLinux:/# uname -a
uname -a
Linux TinaLinux 4.9.191 #719 SMP PREEMPT Tue Nov 5 16:16:32 UTC 2024 aarch64 GNU/Linux

reboot (or halt)
```

## evtest  
* evtest  
```
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
```

## fb-test  
* fb-test  
```
killall -KILL runtrimui.sh MainUI
./fb-test
fb-test 1.0.0 (tablet_rosa)
fb res 1024x768 virtual 1024x16384, line_len 4096
dim 135mm x 216mm
```

## graywin, testsprite
* graywin
```
root@TinaLinux:/# killall -KILL runtrimui.sh MainUI
root@TinaLinux:/# SDL_NOMOUSE=1 /mnt/SDCARD/graywin
root@TinaLinux:/# fbset
fbset

mode "800x600-72"
        # D: 50.000 MHz, H: 48.077 kHz, V: 72.188 Hz
        geometry 800 600 800 600 32
        timings 20000 64 56 23 37 120 6
        accel false
        rgba 0/0,0/0,0/0,0/0
endmode

see code graywin.c:

	width = 800;//640;
	height = 480;//480;
	bpp = 32;//8;
```

## lv_port_linux_frame_buffer, lvgl_demo
* LVGL7 lvgl_demo    
```
killall -KILL runtrimui.sh MainUI

root@TinaLinux:/# killall -KILL runtrimui.sh MainUI
killall -KILL runtrimui.sh MainUI
root@TinaLinux:/# cd /mnt/SDCARD
cd /mnt/SDCARD
root@TinaLinux:/mnt/SDCARD# ./lvgl_demo
./lvgl_demo
The framebuffer device was opened successfully.
1024x768, 32bpp
The framebuffer device was mapped to memory successfully.
unable open evdev interface:: No such file or directory

root@TinaLinux:/# /mnt/SDCARD/evtest
/mnt/SDCARD/evtest
No device specified, trying to scan all of /dev/input/event*
Available devices:
/dev/input/event0:      sunxi-keyboard
/dev/input/event1:      axp2202-pek
/dev/input/event2:      audiocodec sunxi Audio Jack
/dev/input/event3:      TRIMUI Player1
/dev/input/event4:      PixArt USB Optical Mouse
Select the device event number [0-4]:

need back usb-c otg connect a mouse
```
