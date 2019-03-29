# winboot
command-line program useful for dual boot setups

Setup:
          1. copy winboot to your /bin/ directory 
          2. run winboot -h in terminal to read the Configuration Notes, then run winboot.

Configuration Notes:

---------------------------Winboot Version 1.0.5---------------------------------

Winboot needs a little configuration change in /etc/default/grub to work:
          Step 1: Edit the grub configuration file by running: sudo gedit /etc/default/grub
          Step 2: Change the GRUB_DEFAULT parameter so it says GRUB_DEFAULT=\"saved\" then save&exit
          Step 3: Run winboot again"

Disclaimer: Winboot assumes Windows is the second entry on your grub menu (entry number 1, counting from 0), 
          if your setup is different, please change line 19 in the source code to match your preferences! 

-----------------------------------------------------------------------------------
