# Ubuntu-Blank-Screen-after-system-wakeup
How to solve problem: screen remains black after waking up Ubuntu

Open up Terminal
$ sudo gedit /etc/default/grub
Add nouveau.modeset=0 to the line that says GRUB_CMDLINE_LINUX
Save & exit
$ sudo update-grub
Reboot
