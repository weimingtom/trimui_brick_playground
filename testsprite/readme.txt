killall -KILL runtrimui.sh MainUI

SDL_NOMOUSE=1 /mnt/SDCARD/graywin

mode "800x600-72"
        # D: 50.000 MHz, H: 48.077 kHz, V: 72.188 Hz
        geometry 800 600 800 600 32
        timings 20000 64 56 23 37 120 6
        accel false
        rgba 0/0,0/0,0/0,0/0
endmode



-------------


D:\adt-bundle-windows-x86-20140624\sdk\platform-tools>adb push graywin /mnt/SDCARD/
3937 KB/s (1159184 bytes in 0.287s)

D:\adt-bundle-windows-x86-20140624\sdk\platform-tools>adb push icon.bmp /mnt/SDCARD/
41 KB/s (578 bytes in 0.013s)

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
root@TinaLinux:/# /mnt/SDCARD/graywin
/mnt/SDCARD/graywin
SDL_InitSubSystem timer
SDL_InitSubSystem video
Checked mode 1600x1200 at 8 bpp, got mode 1600x1200 at 32 bpp
Checked mode 1408x1056 at 8 bpp, got mode 1408x1056 at 32 bpp
Checked mode 1280x1024 at 8 bpp, got mode 1280x1024 at 32 bpp
Checked mode 1152x864 at 8 bpp, got mode 1152x864 at 32 bpp
Checked mode 1024x768 at 8 bpp, got mode 1024x768 at 32 bpp
Checked mode 960x720 at 8 bpp, got mode 960x720 at 32 bpp
Checked mode 800x600 at 8 bpp, got mode 800x600 at 32 bpp
Checked mode 768x576 at 8 bpp, got mode 768x576 at 32 bpp
Checked mode 720x576 at 8 bpp, got mode 720x576 at 32 bpp
Checked mode 720x480 at 8 bpp, got mode 720x480 at 32 bpp
Checked mode 640x480 at 8 bpp, got mode 640x480 at 32 bpp
Checked mode 640x400 at 8 bpp, got mode 640x400 at 32 bpp
Checked mode 512x384 at 8 bpp, got mode 512x384 at 32 bpp
Checked mode 320x240 at 8 bpp, got mode 320x240 at 32 bpp
Checked mode 320x200 at 8 bpp, got mode 320x200 at 32 bpp
Checked mode 1600x1200 at 16 bpp, got mode 1600x1200 at 16 bpp
No valid timing line for mode 1600x1200
Checked mode 1408x1056 at 16 bpp, got mode 1408x1056 at 16 bpp
Adding mode 1408x1056 at 2 bytes per pixel
Checked mode 1280x1024 at 16 bpp, got mode 1280x1024 at 16 bpp
Adding mode 1280x1024 at 2 bytes per pixel
Checked mode 1152x864 at 16 bpp, got mode 1152x864 at 16 bpp
Adding mode 1152x864 at 2 bytes per pixel
Checked mode 1024x768 at 16 bpp, got mode 1024x768 at 16 bpp
Adding mode 1024x768 at 2 bytes per pixel
Checked mode 960x720 at 16 bpp, got mode 960x720 at 16 bpp
Adding mode 960x720 at 2 bytes per pixel
Checked mode 800x600 at 16 bpp, got mode 800x600 at 16 bpp
Adding mode 800x600 at 2 bytes per pixel
Checked mode 768x576 at 16 bpp, got mode 768x576 at 16 bpp
Adding mode 768x576 at 2 bytes per pixel
Checked mode 720x576 at 16 bpp, got mode 720x576 at 16 bpp
No valid timing line for mode 720x576
Checked mode 720x480 at 16 bpp, got mode 720x480 at 16 bpp
No valid timing line for mode 720x480
Checked mode 640x480 at 16 bpp, got mode 640x480 at 16 bpp
Adding mode 640x480 at 2 bytes per pixel
Checked mode 640x400 at 16 bpp, got mode 640x400 at 16 bpp
Adding mode 640x400 at 2 bytes per pixel
Checked mode 512x384 at 16 bpp, got mode 512x384 at 16 bpp
Adding mode 512x384 at 2 bytes per pixel
Checked mode 320x240 at 16 bpp, got mode 320x240 at 16 bpp
Adding mode 320x240 at 2 bytes per pixel
Checked mode 320x200 at 16 bpp, got mode 320x200 at 16 bpp
Adding mode 320x200 at 2 bytes per pixel
Checked mode 1600x1200 at 24 bpp, got mode 1600x1200 at 24 bpp
No valid timing line for mode 1600x1200
Checked mode 1408x1056 at 24 bpp, got mode 1408x1056 at 24 bpp
Adding mode 1408x1056 at 3 bytes per pixel
Checked mode 1280x1024 at 24 bpp, got mode 1280x1024 at 24 bpp
Adding mode 1280x1024 at 3 bytes per pixel
Checked mode 1152x864 at 24 bpp, got mode 1152x864 at 24 bpp
Adding mode 1152x864 at 3 bytes per pixel
Checked mode 1024x768 at 24 bpp, got mode 1024x768 at 24 bpp
Adding mode 1024x768 at 3 bytes per pixel
Checked mode 960x720 at 24 bpp, got mode 960x720 at 24 bpp
Adding mode 960x720 at 3 bytes per pixel
Checked mode 800x600 at 24 bpp, got mode 800x600 at 24 bpp
Adding mode 800x600 at 3 bytes per pixel
Checked mode 768x576 at 24 bpp, got mode 768x576 at 24 bpp
Adding mode 768x576 at 3 bytes per pixel
Checked mode 720x576 at 24 bpp, got mode 720x576 at 24 bpp
No valid timing line for mode 720x576
Checked mode 720x480 at 24 bpp, got mode 720x480 at 24 bpp
No valid timing line for mode 720x480
Checked mode 640x480 at 24 bpp, got mode 640x480 at 24 bpp
Adding mode 640x480 at 3 bytes per pixel
Checked mode 640x400 at 24 bpp, got mode 640x400 at 24 bpp
Adding mode 640x400 at 3 bytes per pixel
Checked mode 512x384 at 24 bpp, got mode 512x384 at 24 bpp
Adding mode 512x384 at 3 bytes per pixel
Checked mode 320x240 at 24 bpp, got mode 320x240 at 24 bpp
Adding mode 320x240 at 3 bytes per pixel
Checked mode 320x200 at 24 bpp, got mode 320x200 at 24 bpp
Adding mode 320x200 at 3 bytes per pixel
Checked mode 1600x1200 at 32 bpp, got mode 1600x1200 at 32 bpp
No valid timing line for mode 1600x1200
Checked mode 1408x1056 at 32 bpp, got mode 1408x1056 at 32 bpp
Adding mode 1408x1056 at 4 bytes per pixel
Checked mode 1280x1024 at 32 bpp, got mode 1280x1024 at 32 bpp
Adding mode 1280x1024 at 4 bytes per pixel
Checked mode 1152x864 at 32 bpp, got mode 1152x864 at 32 bpp
Adding mode 1152x864 at 4 bytes per pixel
Checked mode 1024x768 at 32 bpp, got mode 1024x768 at 32 bpp
Adding mode 1024x768 at 4 bytes per pixel
Checked mode 960x720 at 32 bpp, got mode 960x720 at 32 bpp
Adding mode 960x720 at 4 bytes per pixel
Checked mode 800x600 at 32 bpp, got mode 800x600 at 32 bpp
Adding mode 800x600 at 4 bytes per pixel
We already have mode 800x600 at 4 bytes per pixel
Checked mode 768x576 at 32 bpp, got mode 768x576 at 32 bpp
Adding mode 768x576 at 4 bytes per pixel
Checked mode 720x576 at 32 bpp, got mode 720x576 at 32 bpp
No valid timing line for mode 720x576
Checked mode 720x480 at 32 bpp, got mode 720x480 at 32 bpp
No valid timing line for mode 720x480
Checked mode 640x480 at 32 bpp, got mode 640x480 at 32 bpp
Adding mode 640x480 at 4 bytes per pixel
Checked mode 640x400 at 32 bpp, got mode 640x400 at 32 bpp
Adding mode 640x400 at 4 bytes per pixel
Checked mode 512x384 at 32 bpp, got mode 512x384 at 32 bpp
Adding mode 512x384 at 4 bytes per pixel
Checked mode 320x240 at 32 bpp, got mode 320x240 at 32 bpp
Adding mode 320x240 at 4 bytes per pixel
Checked mode 320x200 at 32 bpp, got mode 320x200 at 32 bpp
Adding mode 320x200 at 4 bytes per pixel
FB_VideoInit 1
FB_VideoInit 2
FB_VideoInit 3 FB_OpenKeyboard
FB_VideoInit 4 FB_OpenMouse
FB_VideoInit 4 FB_OpenMouse failed
Couldn't initialize SDL: Unable to open mouse
root@TinaLinux:/# SDL_NOMOUSE=1 /mnt/SDCARD/graywin
SDL_NOMOUSE=1 /mnt/SDCARD/graywin
SDL_InitSubSystem timer
SDL_InitSubSystem video
Checked mode 1600x1200 at 8 bpp, got mode 1600x1200 at 32 bpp
Checked mode 1408x1056 at 8 bpp, got mode 1408x1056 at 32 bpp
Checked mode 1280x1024 at 8 bpp, got mode 1280x1024 at 32 bpp
Checked mode 1152x864 at 8 bpp, got mode 1152x864 at 32 bpp
Checked mode 1024x768 at 8 bpp, got mode 1024x768 at 32 bpp
Checked mode 960x720 at 8 bpp, got mode 960x720 at 32 bpp
Checked mode 800x600 at 8 bpp, got mode 800x600 at 32 bpp
Checked mode 768x576 at 8 bpp, got mode 768x576 at 32 bpp
Checked mode 720x576 at 8 bpp, got mode 720x576 at 32 bpp
Checked mode 720x480 at 8 bpp, got mode 720x480 at 32 bpp
Checked mode 640x480 at 8 bpp, got mode 640x480 at 32 bpp
Checked mode 640x400 at 8 bpp, got mode 640x400 at 32 bpp
Checked mode 512x384 at 8 bpp, got mode 512x384 at 32 bpp
Checked mode 320x240 at 8 bpp, got mode 320x240 at 32 bpp
Checked mode 320x200 at 8 bpp, got mode 320x200 at 32 bpp
Checked mode 1600x1200 at 16 bpp, got mode 1600x1200 at 16 bpp
No valid timing line for mode 1600x1200
Checked mode 1408x1056 at 16 bpp, got mode 1408x1056 at 16 bpp
Adding mode 1408x1056 at 2 bytes per pixel
Checked mode 1280x1024 at 16 bpp, got mode 1280x1024 at 16 bpp
Adding mode 1280x1024 at 2 bytes per pixel
Checked mode 1152x864 at 16 bpp, got mode 1152x864 at 16 bpp
Adding mode 1152x864 at 2 bytes per pixel
Checked mode 1024x768 at 16 bpp, got mode 1024x768 at 16 bpp
Adding mode 1024x768 at 2 bytes per pixel
Checked mode 960x720 at 16 bpp, got mode 960x720 at 16 bpp
Adding mode 960x720 at 2 bytes per pixel
Checked mode 800x600 at 16 bpp, got mode 800x600 at 16 bpp
Adding mode 800x600 at 2 bytes per pixel
Checked mode 768x576 at 16 bpp, got mode 768x576 at 16 bpp
Adding mode 768x576 at 2 bytes per pixel
Checked mode 720x576 at 16 bpp, got mode 720x576 at 16 bpp
No valid timing line for mode 720x576
Checked mode 720x480 at 16 bpp, got mode 720x480 at 16 bpp
No valid timing line for mode 720x480
Checked mode 640x480 at 16 bpp, got mode 640x480 at 16 bpp
Adding mode 640x480 at 2 bytes per pixel
Checked mode 640x400 at 16 bpp, got mode 640x400 at 16 bpp
Adding mode 640x400 at 2 bytes per pixel
Checked mode 512x384 at 16 bpp, got mode 512x384 at 16 bpp
Adding mode 512x384 at 2 bytes per pixel
Checked mode 320x240 at 16 bpp, got mode 320x240 at 16 bpp
Adding mode 320x240 at 2 bytes per pixel
Checked mode 320x200 at 16 bpp, got mode 320x200 at 16 bpp
Adding mode 320x200 at 2 bytes per pixel
Checked mode 1600x1200 at 24 bpp, got mode 1600x1200 at 24 bpp
No valid timing line for mode 1600x1200
Checked mode 1408x1056 at 24 bpp, got mode 1408x1056 at 24 bpp
Adding mode 1408x1056 at 3 bytes per pixel
Checked mode 1280x1024 at 24 bpp, got mode 1280x1024 at 24 bpp
Adding mode 1280x1024 at 3 bytes per pixel
Checked mode 1152x864 at 24 bpp, got mode 1152x864 at 24 bpp
Adding mode 1152x864 at 3 bytes per pixel
Checked mode 1024x768 at 24 bpp, got mode 1024x768 at 24 bpp
Adding mode 1024x768 at 3 bytes per pixel
Checked mode 960x720 at 24 bpp, got mode 960x720 at 24 bpp
Adding mode 960x720 at 3 bytes per pixel
Checked mode 800x600 at 24 bpp, got mode 800x600 at 24 bpp
Adding mode 800x600 at 3 bytes per pixel
Checked mode 768x576 at 24 bpp, got mode 768x576 at 24 bpp
Adding mode 768x576 at 3 bytes per pixel
Checked mode 720x576 at 24 bpp, got mode 720x576 at 24 bpp
No valid timing line for mode 720x576
Checked mode 720x480 at 24 bpp, got mode 720x480 at 24 bpp
No valid timing line for mode 720x480
Checked mode 640x480 at 24 bpp, got mode 640x480 at 24 bpp
Adding mode 640x480 at 3 bytes per pixel
Checked mode 640x400 at 24 bpp, got mode 640x400 at 24 bpp
Adding mode 640x400 at 3 bytes per pixel
Checked mode 512x384 at 24 bpp, got mode 512x384 at 24 bpp
Adding mode 512x384 at 3 bytes per pixel
Checked mode 320x240 at 24 bpp, got mode 320x240 at 24 bpp
Adding mode 320x240 at 3 bytes per pixel
Checked mode 320x200 at 24 bpp, got mode 320x200 at 24 bpp
Adding mode 320x200 at 3 bytes per pixel
Checked mode 1600x1200 at 32 bpp, got mode 1600x1200 at 32 bpp
No valid timing line for mode 1600x1200
Checked mode 1408x1056 at 32 bpp, got mode 1408x1056 at 32 bpp
Adding mode 1408x1056 at 4 bytes per pixel
Checked mode 1280x1024 at 32 bpp, got mode 1280x1024 at 32 bpp
Adding mode 1280x1024 at 4 bytes per pixel
Checked mode 1152x864 at 32 bpp, got mode 1152x864 at 32 bpp
Adding mode 1152x864 at 4 bytes per pixel
Checked mode 1024x768 at 32 bpp, got mode 1024x768 at 32 bpp
Adding mode 1024x768 at 4 bytes per pixel
Checked mode 960x720 at 32 bpp, got mode 960x720 at 32 bpp
Adding mode 960x720 at 4 bytes per pixel
Checked mode 800x600 at 32 bpp, got mode 800x600 at 32 bpp
Adding mode 800x600 at 4 bytes per pixel
We already have mode 800x600 at 4 bytes per pixel
Checked mode 768x576 at 32 bpp, got mode 768x576 at 32 bpp
Adding mode 768x576 at 4 bytes per pixel
Checked mode 720x576 at 32 bpp, got mode 720x576 at 32 bpp
No valid timing line for mode 720x576
Checked mode 720x480 at 32 bpp, got mode 720x480 at 32 bpp
No valid timing line for mode 720x480
Checked mode 640x480 at 32 bpp, got mode 640x480 at 32 bpp
Adding mode 640x480 at 4 bytes per pixel
Checked mode 640x400 at 32 bpp, got mode 640x400 at 32 bpp
Adding mode 640x400 at 4 bytes per pixel
Checked mode 512x384 at 32 bpp, got mode 512x384 at 32 bpp
Adding mode 512x384 at 4 bytes per pixel
Checked mode 320x240 at 32 bpp, got mode 320x240 at 32 bpp
Adding mode 320x240 at 4 bytes per pixel
Checked mode 320x200 at 32 bpp, got mode 320x200 at 32 bpp
Adding mode 320x200 at 4 bytes per pixel
FB_VideoInit 1
FB_VideoInit 2
FB_VideoInit 3 FB_OpenKeyboard
FB_VideoInit 4 FB_OpenMouse
FB_VideoInit 4 FB_OpenMouse failed
FB_VideoInit 5 return
SDL_AllocFormat 1
SDL_AllocFormat 2
SDL_AllocFormat 5 return, 0
SDL_InitSubSystem audio
SDL_InitSubSystem joystick
SDL_InitSubSystem cdrom
SDL_InitSubSystem return
SDL_SetVideoMode 1
SDL_SetVideoMode 2
SDL_SetVideoMode 3
SDL_SetVideoMode 4
SDL_SetVideoMode 5
SDL_SetVideoMode 5.1
SDL_SetVideoMode 5.2
SDL_SetVideoMode 5.3
SDL_SetVideoMode 5.4
FB_SetVideoMode 1
FB_EnterGraphicsMode 1
FB_EnterGraphicsMode 11 return
FB_SetVideoMode 2
FB_SetVideoMode 3
Printing original vinfo:
Printing vinfo:
        xres: 800
        yres: 600
        xres_virtual: 800
        yres_virtual: 600
        xoffset: 0
        yoffset: 0
        bits_per_pixel: 32
        grayscale: 0
        nonstd: 0
        activate: 0
        height: 216
        width: 135
        accel_flags: 0
        pixclock: 20000
        left_margin: 64
        right_margin: 56
        upper_margin: 23
        lower_margin: 37
        hsync_len: 120
        vsync_len: 6
        sync: 3
        vmode: 0
        red: 0/0
        green: 0/0
        blue: 0/0
        alpha: 0/0
Printing actual vinfo:
Printing vinfo:
        xres: 800
        yres: 600
        xres_virtual: 800
        yres_virtual: 600
        xoffset: 0
        yoffset: 0
        bits_per_pixel: 32
        grayscale: 0
        nonstd: 0
        activate: 0
        height: 216
        width: 135
        accel_flags: 0
        pixclock: 20000
        left_margin: 64
        right_margin: 56
        upper_margin: 23
        lower_margin: 37
        hsync_len: 120
        vsync_len: 6
        sync: 3
        vmode: 0
        red: 0/0
        green: 0/0
        blue: 0/0
        alpha: 0/0
SDL_ReallocFormat 1, Amask=ff000000
SDL_ReallocFormat 2, Amask=ff000000
SDL_AllocFormat 1
SDL_AllocFormat 2
SDL_AllocFormat 3, Amask=ff000000
SDL_AllocFormat 4, ff000000
SDL_AllocFormat 5 return, ff000000
SDL_SetVideoMode 5.5
SDL_SetVideoMode 5.5.1
SDL_SetVideoMode 6
SDL_SetVideoMode 7
SDL_SetVideoMode 8
SDL_SetVideoMode 9
SDL_AllocFormat 1
SDL_AllocFormat 2
SDL_AllocFormat 3, Amask=0
SDL_AllocFormat 4, 0
SDL_AllocFormat 5 return, 0
SDL_SetVideoMode 10 return
Couldn't load icon.bmp: Couldn't open icon.bmproot@TinaLinux:/# ls
ls
bin         lib64       overlay     root        usr
dev         lost+found  proc        sbin        var
etc         mnt         rdinit      sys         www
lib         mono        rom         tmp
root@TinaLinux:/# cd /mnt/SDCARD
cd /mnt/SDCARD
root@TinaLinux:/mnt/SDCARD# SDL_NOMOUSE=1 /mnt/SDCARD/graywin
SDL_NOMOUSE=1 /mnt/SDCARD/graywin
SDL_InitSubSystem timer
SDL_InitSubSystem video
Checked mode 1600x1200 at 8 bpp, got mode 1600x1200 at 32 bpp
Checked mode 1408x1056 at 8 bpp, got mode 1408x1056 at 32 bpp
Checked mode 1280x1024 at 8 bpp, got mode 1280x1024 at 32 bpp
Checked mode 1152x864 at 8 bpp, got mode 1152x864 at 32 bpp
Checked mode 1024x768 at 8 bpp, got mode 1024x768 at 32 bpp
Checked mode 960x720 at 8 bpp, got mode 960x720 at 32 bpp
Checked mode 800x600 at 8 bpp, got mode 800x600 at 32 bpp
Checked mode 768x576 at 8 bpp, got mode 768x576 at 32 bpp
Checked mode 720x576 at 8 bpp, got mode 720x576 at 32 bpp
Checked mode 720x480 at 8 bpp, got mode 720x480 at 32 bpp
Checked mode 640x480 at 8 bpp, got mode 640x480 at 32 bpp
Checked mode 640x400 at 8 bpp, got mode 640x400 at 32 bpp
Checked mode 512x384 at 8 bpp, got mode 512x384 at 32 bpp
Checked mode 320x240 at 8 bpp, got mode 320x240 at 32 bpp
Checked mode 320x200 at 8 bpp, got mode 320x200 at 32 bpp
Checked mode 1600x1200 at 16 bpp, got mode 1600x1200 at 16 bpp
No valid timing line for mode 1600x1200
Checked mode 1408x1056 at 16 bpp, got mode 1408x1056 at 16 bpp
Adding mode 1408x1056 at 2 bytes per pixel
Checked mode 1280x1024 at 16 bpp, got mode 1280x1024 at 16 bpp
Adding mode 1280x1024 at 2 bytes per pixel
Checked mode 1152x864 at 16 bpp, got mode 1152x864 at 16 bpp
Adding mode 1152x864 at 2 bytes per pixel
Checked mode 1024x768 at 16 bpp, got mode 1024x768 at 16 bpp
Adding mode 1024x768 at 2 bytes per pixel
Checked mode 960x720 at 16 bpp, got mode 960x720 at 16 bpp
Adding mode 960x720 at 2 bytes per pixel
Checked mode 800x600 at 16 bpp, got mode 800x600 at 16 bpp
Adding mode 800x600 at 2 bytes per pixel
Checked mode 768x576 at 16 bpp, got mode 768x576 at 16 bpp
Adding mode 768x576 at 2 bytes per pixel
Checked mode 720x576 at 16 bpp, got mode 720x576 at 16 bpp
No valid timing line for mode 720x576
Checked mode 720x480 at 16 bpp, got mode 720x480 at 16 bpp
No valid timing line for mode 720x480
Checked mode 640x480 at 16 bpp, got mode 640x480 at 16 bpp
Adding mode 640x480 at 2 bytes per pixel
Checked mode 640x400 at 16 bpp, got mode 640x400 at 16 bpp
Adding mode 640x400 at 2 bytes per pixel
Checked mode 512x384 at 16 bpp, got mode 512x384 at 16 bpp
Adding mode 512x384 at 2 bytes per pixel
Checked mode 320x240 at 16 bpp, got mode 320x240 at 16 bpp
Adding mode 320x240 at 2 bytes per pixel
Checked mode 320x200 at 16 bpp, got mode 320x200 at 16 bpp
Adding mode 320x200 at 2 bytes per pixel
Checked mode 1600x1200 at 24 bpp, got mode 1600x1200 at 24 bpp
No valid timing line for mode 1600x1200
Checked mode 1408x1056 at 24 bpp, got mode 1408x1056 at 24 bpp
Adding mode 1408x1056 at 3 bytes per pixel
Checked mode 1280x1024 at 24 bpp, got mode 1280x1024 at 24 bpp
Adding mode 1280x1024 at 3 bytes per pixel
Checked mode 1152x864 at 24 bpp, got mode 1152x864 at 24 bpp
Adding mode 1152x864 at 3 bytes per pixel
Checked mode 1024x768 at 24 bpp, got mode 1024x768 at 24 bpp
Adding mode 1024x768 at 3 bytes per pixel
Checked mode 960x720 at 24 bpp, got mode 960x720 at 24 bpp
Adding mode 960x720 at 3 bytes per pixel
Checked mode 800x600 at 24 bpp, got mode 800x600 at 24 bpp
Adding mode 800x600 at 3 bytes per pixel
Checked mode 768x576 at 24 bpp, got mode 768x576 at 24 bpp
Adding mode 768x576 at 3 bytes per pixel
Checked mode 720x576 at 24 bpp, got mode 720x576 at 24 bpp
No valid timing line for mode 720x576
Checked mode 720x480 at 24 bpp, got mode 720x480 at 24 bpp
No valid timing line for mode 720x480
Checked mode 640x480 at 24 bpp, got mode 640x480 at 24 bpp
Adding mode 640x480 at 3 bytes per pixel
Checked mode 640x400 at 24 bpp, got mode 640x400 at 24 bpp
Adding mode 640x400 at 3 bytes per pixel
Checked mode 512x384 at 24 bpp, got mode 512x384 at 24 bpp
Adding mode 512x384 at 3 bytes per pixel
Checked mode 320x240 at 24 bpp, got mode 320x240 at 24 bpp
Adding mode 320x240 at 3 bytes per pixel
Checked mode 320x200 at 24 bpp, got mode 320x200 at 24 bpp
Adding mode 320x200 at 3 bytes per pixel
Checked mode 1600x1200 at 32 bpp, got mode 1600x1200 at 32 bpp
No valid timing line for mode 1600x1200
Checked mode 1408x1056 at 32 bpp, got mode 1408x1056 at 32 bpp
Adding mode 1408x1056 at 4 bytes per pixel
Checked mode 1280x1024 at 32 bpp, got mode 1280x1024 at 32 bpp
Adding mode 1280x1024 at 4 bytes per pixel
Checked mode 1152x864 at 32 bpp, got mode 1152x864 at 32 bpp
Adding mode 1152x864 at 4 bytes per pixel
Checked mode 1024x768 at 32 bpp, got mode 1024x768 at 32 bpp
Adding mode 1024x768 at 4 bytes per pixel
Checked mode 960x720 at 32 bpp, got mode 960x720 at 32 bpp
Adding mode 960x720 at 4 bytes per pixel
Checked mode 800x600 at 32 bpp, got mode 800x600 at 32 bpp
Adding mode 800x600 at 4 bytes per pixel
We already have mode 800x600 at 4 bytes per pixel
Checked mode 768x576 at 32 bpp, got mode 768x576 at 32 bpp
Adding mode 768x576 at 4 bytes per pixel
Checked mode 720x576 at 32 bpp, got mode 720x576 at 32 bpp
No valid timing line for mode 720x576
Checked mode 720x480 at 32 bpp, got mode 720x480 at 32 bpp
No valid timing line for mode 720x480
Checked mode 640x480 at 32 bpp, got mode 640x480 at 32 bpp
Adding mode 640x480 at 4 bytes per pixel
Checked mode 640x400 at 32 bpp, got mode 640x400 at 32 bpp
Adding mode 640x400 at 4 bytes per pixel
Checked mode 512x384 at 32 bpp, got mode 512x384 at 32 bpp
Adding mode 512x384 at 4 bytes per pixel
Checked mode 320x240 at 32 bpp, got mode 320x240 at 32 bpp
Adding mode 320x240 at 4 bytes per pixel
Checked mode 320x200 at 32 bpp, got mode 320x200 at 32 bpp
Adding mode 320x200 at 4 bytes per pixel
FB_VideoInit 1
FB_VideoInit 2
FB_VideoInit 3 FB_OpenKeyboard
FB_VideoInit 4 FB_OpenMouse
FB_VideoInit 4 FB_OpenMouse failed
FB_VideoInit 5 return
SDL_AllocFormat 1
SDL_AllocFormat 2
SDL_AllocFormat 5 return, 0
SDL_InitSubSystem audio
SDL_InitSubSystem joystick
SDL_InitSubSystem cdrom
SDL_InitSubSystem return
SDL_SetVideoMode 1
SDL_SetVideoMode 2
SDL_SetVideoMode 3
SDL_SetVideoMode 4
SDL_SetVideoMode 5
SDL_SetVideoMode 5.1
SDL_SetVideoMode 5.2
SDL_SetVideoMode 5.3
SDL_SetVideoMode 5.4
FB_SetVideoMode 1
FB_EnterGraphicsMode 1
FB_EnterGraphicsMode 11 return
FB_SetVideoMode 2
FB_SetVideoMode 3
Printing original vinfo:
Printing vinfo:
        xres: 800
        yres: 600
        xres_virtual: 800
        yres_virtual: 600
        xoffset: 0
        yoffset: 0
        bits_per_pixel: 32
        grayscale: 0
        nonstd: 0
        activate: 0
        height: 216
        width: 135
        accel_flags: 0
        pixclock: 20000
        left_margin: 64
        right_margin: 56
        upper_margin: 23
        lower_margin: 37
        hsync_len: 120
        vsync_len: 6
        sync: 3
        vmode: 0
        red: 0/0
        green: 0/0
        blue: 0/0
        alpha: 0/0
Printing actual vinfo:
Printing vinfo:
        xres: 800
        yres: 600
        xres_virtual: 800
        yres_virtual: 600
        xoffset: 0
        yoffset: 0
        bits_per_pixel: 32
        grayscale: 0
        nonstd: 0
        activate: 0
        height: 216
        width: 135
        accel_flags: 0
        pixclock: 20000
        left_margin: 64
        right_margin: 56
        upper_margin: 23
        lower_margin: 37
        hsync_len: 120
        vsync_len: 6
        sync: 3
        vmode: 0
        red: 0/0
        green: 0/0
        blue: 0/0
        alpha: 0/0
SDL_ReallocFormat 1, Amask=ff000000
SDL_ReallocFormat 2, Amask=ff000000
SDL_AllocFormat 1
SDL_AllocFormat 2
SDL_AllocFormat 3, Amask=ff000000
SDL_AllocFormat 4, ff000000
SDL_AllocFormat 5 return, ff000000
SDL_SetVideoMode 5.5
SDL_SetVideoMode 5.5.1
SDL_SetVideoMode 6
SDL_SetVideoMode 7
SDL_SetVideoMode 8
SDL_SetVideoMode 9
SDL_AllocFormat 1
SDL_AllocFormat 2
SDL_AllocFormat 3, Amask=0
SDL_AllocFormat 4, 0
SDL_AllocFormat 5 return, 0
SDL_SetVideoMode 10 return
SDL_AllocFormat 1
SDL_AllocFormat 2
SDL_AllocFormat 5 return, 0
SDL_AllocFormat 1
SDL_AllocFormat 2
SDL_AllocFormat 3, Amask=0
SDL_AllocFormat 4, 0
SDL_AllocFormat 5 return, 0
Screen is at 32 bits per pixel
Screen is in system memory
Sprite is in system memory
Sprite blit uses RLE acceleration


