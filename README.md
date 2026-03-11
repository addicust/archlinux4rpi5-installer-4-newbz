# ArchLinuxARM Installer for RPI-5 and RPI Zero 2W

###just got the scipt to install on a 128gb usb stick using RASPIOS trixie 64bit on a pi zero 2w
###tried on an nvme hat on my pi 5 using alarm and it failed to partition usinf sfdisk, i partitioned it manually using fdisk commented out the a4pPart function call at the bottom of the program, IT FAILED TO BOOT, ALMOST CERTAINLY DUE TO THE FSTAB, LOOKING INTO FIXING SOON

With some tweaking it should work  on sd, usb, and nvme.

Shamefully programmed using duckai, proudly tested on a raspberry pi zero 2w (all my pi5 OS work on the pi zero 2w).  I used a lot of help off the internet.

My goal is to polish this turd so that any novice, even myself 4 months ago, can install arch linux on raspberry pi 5.  Hyprland works really well on a 16g pi5 and would work similarly on a 4g or 8g version.

If I finish all the features planned I might get ambitious and set up a chroot helper to use a arch linux arm on SD card for example to encrypt arch linux arm on nvme or usb.


 HOW TO
Run as superuser
# sudo ./a4p

The easiest way to use this scipt is to edit the default variables at the top of the program, and then press y at the main menu and y again for confirmation, but one can also use the menu.

YOU MUST follow the after boot instructions to get the fan speed controller to work among other things.  FEAR NOT, if your fan is running full blast upon first boot, nothing is getting hot, upon following after boot and rebooting the fan speed will be under control.

login as root user root is username and password

type cat afterBoot.txt

type the commands in one at a time in the order they appear in

reboot

login as root to install sudo and stuff set locale and all of that.

login as alarm username alarm password alarm

I know this is a ugly, this is my first repo, and the extent of my coding skills is writing bash scripts, with help from online.

 DISCLAIMER
I am not liable for anything, anywhere, for any reasons. Running a script as root you have not looked over is a bad idea.  This scipt will allow you to destroy your computer if used.  Most anything fun is illegal in california, and causes cancer, including this script.
