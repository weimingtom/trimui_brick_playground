killall -KILL runtrimui.sh MainUI

SDL_NOMOUSE=1 /mnt/SDCARD/graywin

root@TinaLinux:/# fbset
fbset

mode "800x600-72"
        # D: 50.000 MHz, H: 48.077 kHz, V: 72.188 Hz
        geometry 800 600 800 600 32
        timings 20000 64 56 23 37 120 6
        accel false
        rgba 0/0,0/0,0/0,0/0
endmode

----------------

see code graywin.c:

	width = 800;//640;
	height = 480;//480;
	bpp = 32;//8;
