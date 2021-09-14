# Ubuntu-Blank-Screen-after-system-wakeup
How to solve problem: screen remains black after waking up Ubuntu

1. Open up Terminal <br>
2. $ sudo gedit /etc/default/grub <br>
3. Add nouveau.modeset=0 to the line that says GRUB_CMDLINE_LINUX <br>
4. Save & exit <br>
5. $ sudo update-grub <br>
6. Reboot
