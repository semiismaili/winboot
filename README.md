# winboot
command-line program useful for dual boot setups
Setup:
1. copy winboot to your /bin/ directory 
2. run winboot -h in terminal to read the Configuration Notes, then run winboot.

Configuration Notes:
echo "---------------------------Winboot Version 1.0.5---------------------------------"
echo " "
echo "Winboot needs a little configuration change in /etc/default/grub to work:"
echo "Step 1: Edit the grub configuration file by running: sudo gedit /etc/default/grub"
echo "Step 2: Change the GRUB_DEFAULT parameter so it says GRUB_DEFAULT=\"saved\" then save&exit"
echo "Step 3: Run winboot again"
echo " "
echo "Disclaimer: Winboot assumes Windows is the second entry on your grub menu (entry number 1, counting from 0), "
echo "            if your setup is different, please change line 19 in the source code to match your preferences! "
echo ""
echo "-----------------------------------------------------------------------------------"
