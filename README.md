# Ubuntu-Blank-Screen-after-system-wakeup
How to solve problem: screen remains black after waking up Ubuntu

Open up Terminal <br>
$ sudo gedit /etc/default/grub <br>
Add nouveau.modeset=0 to the line that says GRUB_CMDLINE_LINUX <br>
Save & exit <br>
$ sudo update-grub <br>
Reboot
