# archlinux4rpi5-installer-4-newbz
I created a clumsy arch linux installer for raspberry pi,  with some tweaking it should work  on sd, usb, and nvme.  I got it to install on a 128gb usb today.
shamefully programmed using duck duck go in bash, proudly tested on a raspberry pi zero 2w (all my pi5 OS work on the pi zero 2w).  I stole a lot of help off the internet. in short order I will source all help and references used.
my goal is to polish this turd so that any dummy, even myself 4 months ago, can install arch linux on raspberry pi 5.  hyprland works really well on a 16g pi5.

if i finish all the features i have planned i might get ambitious and set up a chroot helper to use a arch linux arm on SD card for example to encrypt arch linux arm on nvme or usb.


HOW TO

To use this scipt the easiest way is to edit the default variables at the top of the program, but i included a menu that should help even the noobest pf newbs to get started on making a bootable arch for pi5 sd card or usb device.
In the future i will set it up so you can pipe yes into it after changing default if, for some reason, you are writing many SD's

YOU MUST follow the after boot instructions to get the fan speed controller to work among other things.  FEAR NOT, if your fan is running full blast upon first boot, nothing is getting hot, upon following after boot and rebooting the fan speed will be under control.

I know this is a horrible ugly mess, this is my first repo, and the extent of my coding skills is writing bash scripts, with help from online.



if i am able to choose a license it is gpl2, please dont sue me,  i am not liable for anything anywhere for any reasons, no commercial use you freeloading capitalists.
