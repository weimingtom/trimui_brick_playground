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

## Cross compiling godot 3.5.1   
* unzip frt-2.1.0.zip to godot-3.5.1/platform/frt/.  
https://github.com/efornara/frt/releases/tag/2.1.0    
https://github.com/godotengine/godot/releases/tag/3.5.1-stable    
https://github.com/godotengine/godot-demo-projects/releases/tag/3.5-9e68af3  
https://github.com/godotengine/godot-demo-projects/releases/download/3.5-9e68af3/2d_pong.zip   
godot.frt.opt.arm64v8  
include_trimui.tar.gz  
pong_v1_3.5.1.tar.gz  
frt-2.1.0.zip  
godot-3.5.1-stable.tar.xz  
* PC version build: (need multi cores CPUs)    
$ scons p=frt tools=no target=debug -j8    
(cp bin/godot.frt.debug to pong/)    
$ cd ../pong/  
$ ./godot.frt.debug  
* Cross compiling:  
PATH=/home/wmt/work_trimui/aarch64-linux-gnu-7.5.0-linaro/bin:$PATH scons platform=frt frt_arch=arm64v8 frt_cross=auto tools=no target=release verbose=yes CCFLAGS='-I/home/wmt/work_trimui/usr/include -I/home/wmt/work_trimui/usr/include/SDL2' LINKFLAGS='-lSDL2 -L/home/wmt/work_trimui/usr/lib' -j8  
```
1.
Mod /platform/frt/SCsub:

frt_env = env.Clone()
#frt_env.ParseConfig(env['FRT_PKG_CONFIG'] + ' sdl2 --cflags --libs')
#frt_env.ParseConfig('./sdl2-config --cflags --libs')
frt_env.Append(CCFLAGS=['-I/home/wmt/work_trimui/usr/include'])
frt_env.Append(CCFLAGS=['-I/home/wmt/work_trimui/usr/include/SDL2'])
frt_env.Append(CCFLAGS=['-D_REENTRANT'])
frt_env.Append(LDFLAGS=['-L/home/wmt/work_trimui/usr/lib'])

2.
(clean /home/wmt/work_trimui/usr/include)
see include_trimui.tar.gz

3.
need mod /home/wmt/work_godot/godot-3.5.1-stable/thirdparty/libvpx/vp8/common/generic/systemdependent.c:102
to 0
#if ARCH_ARM
    ctx->cpu_caps = 0;//arm_cpu_caps();

	
4.
PATH=/home/wmt/work_trimui/aarch64-linux-gnu-7.5.0-linaro/bin:$PATH scons platform=frt frt_arch=arm64v8 frt_cross=auto tools=no target=release verbose=yes CCFLAGS='-I/home/wmt/work_trimui/usr/include -I/home/wmt/work_trimui/usr/include/SDL2' LINKFLAGS='-lSDL2 -L/home/wmt/work_trimui/usr/lib' -j8
```
```
今天我可以成功交叉编译arm6版的godot 3.5.1无tools版，可以在trimui smart pro上运行。
编译方法大概是这样（虽然有一个链接问题未完全解决）：
（1）去掉platform/frt/SCsub中关于FRT_PKG_CONFIG的调用，换成frt_env.Append
（2）确保交叉工具链的/usr/include文件夹只包含很少文件，
避免和godot内的库版本不同而编译失败
（3）libvpx有一处获取CPU特性的代码，我改成返回0
（4）用scons交叉编译，通过frt_arch和CCFLAGS和LINKFLAGS指定交叉编译参数，
用PATH环境变量导入gcc程序目录

关于godot mono，上次说的动态AddChild和Instantiate，我没有详细研究，
其实我目前看到有两种动态Instantiate实例化的写法，都是基于
PackedScene.Instantiate（可以强制转换返回值，或者使用泛型类型参数）。
这两种写法区别在于，一种是需要(PackedScene)ResourceLoader.Load("res://tscn路径")
获取PackedScene对象，然后再实例化（感觉像是写ActionScript3），
还有一种是在C井中用Export标注来导出属性，然后在godot编辑器-检查器-修改这个属性指定场景，
从而获取PackedScene对象，然后再PackedScene.Instantiate实例化。
相对而言第一种写法可以没那么依靠godot编辑器，更依靠于字符串，
而不需要手工绑定到tscn场景文件
```

## Cross compiling PPSSPP 1.5.4  
* imouto.iso    
* ppsspp_v1.5.4_min.tar.gz  
* CMAKE_BUILD_TYPE=debug  
```
ppsspp闪退好像是因为一个函数sceMpegAvcDecode出问题，不过可能升级到最新版就会没事，
问题是我不会编译这个，等以后有时间再研究  

我试过可以很容易在xubuntu 20下编译PC版linux版的PPSSPP，前提是要
git submodule update --init，如果不做子模块导出的话，
直接cmake会提示错误，简单来说就是不能下官方的zip源码包，
而是应该检出tag版本，例如git checkout v1.5.4，
最好预留两三G的硬盘，然后直接cmake和make即可编译成功
——可能只是用了一下OpenGL和SDL2的系统库，其他大多数库都是静态链接的

关于linux掌机跑psp自制游戏会闪退的问题，我现在可以在xubuntu 20下
编译PPSSPP 1.5.4版并且正确运行会在linux掌机上闪退的自制游戏
（这个移植游戏不是我做的）——事实上我编译默认release版，
跑这个游戏也会闪退，只不过我找到解决办法，
就是把CMakeCache.txt的CMAKE_BUILD_TYPE的值改成debug（默认空白），
然后再编译一次即可，体积会增加一倍，但好处是不会出现闪退的情况。
当然这只是对于1.5.4版而言，最新版估计也能用类似的方法解决
```
