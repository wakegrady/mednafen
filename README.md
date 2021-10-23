# mednafen

sudo apt-get install mednafen libsdl2-dev
wget "http://download.freeroms.com/nes_roms/08/super_mario_bros._3.zip"

#use the provided config file
#config file should be located in ~/.mednafen/
#you'll need to run mednafen once so it can create the default config files.
#if you want to manually edit your exisiting config file
#do this (Note that trailing spaces on lines will cause errors):

find the line "video.driver opengl" and change it to "video.driver sdl"
change "sound.device default" to "sound.device sexyal-literal-default"
nes.stretch full
nes.xres 648
nes.yres 432
;Enable fullscreen mode.
video.fs 1

#648x432 is my screen rez.  check yours by running "xrandr"
