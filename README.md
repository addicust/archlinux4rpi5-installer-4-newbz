# ArchLinuxARM Installer for RPI-5 and RPI Zero 2W
With some tweaking it should work  on sd, usb, and nvme.

Shamefully programmed using duckai, proudly tested on a raspberry pi zero 2w (all my pi5 OS work on the pi zero 2w).  I used a lot of help off the internet.

My goal is to polish this turd so that any novice, even myself 4 months ago, can install arch linux on raspberry pi 5.  Hyprland works really well on a 16g pi5 and would work similarly on a 4g or 8g version.

If I finish all the features planned I might get ambitious and set up a chroot helper to use a arch linux arm on SD card for example to encrypt arch linux arm on nvme or usb.


 HOW TO
Run as superuser
# sudo ./a4p

The easiest way to use this scipt is to edit the default variables at the top of the program, and then press y at the main menu and y again for confirmation, but one can also use the menu.

YOU MUST follow the after boot instructions to get the fan speed controller to work among other things.  FEAR NOT, if your fan is running full blast upon first boot, nothing is getting hot, upon following after boot and rebooting the fan speed will be under control.

I know this is a ugly, this is my first repo, and the extent of my coding skills is writing bash scripts, with help from online.

 DISCLAIMER
I am not liable for anything, anywhere, for any reasons. Running a script as root you have not looked over is a bad idea.  This scipt will allow you to destroy your computer if used.  Most anything fun is illegal in california, and causes cancer, including this script.
