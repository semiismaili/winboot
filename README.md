# winboot
useful for dual boot setups

**Winboot** is a shell script that reboots directly into Windows from your Linux session, without having to select it from the grub menu. *For all those times you forget to do it and your grub timer runs out.*

Installation:
-
          1. Open up a terminal 
          
          2. Run the following commands:
                    
                    git clone https://github.com/semiismaili/Winboot.git
                    
                    cd Winboot
                    
                    chmod 755 winboot
                    
                    ./winboot -install
                    


Usage:
-
          winboot (reboots to windows)
          
          winboot -h (brings this screen)
          
          winboot -update (updates to latest version from repository)
          
          winboot -install (initial one-time only installation)

          sudo winboot -set <your_entry_number>  (changes the windows entry number to <your_entry_number>)
          
  
Configuration Troubleshooter:
-
Winboot may need a little configuration change in /etc/default/grub to work, if winboot doesn't reboot you into Windows
please try the following steps:


    Step 1: Edit the grub configuration file by running: sudo gedit /etc/default/grub

    Step 2: Change the GRUB_DEFAULT parameter so it says GRUB_DEFAULT="saved" then save&exit



Send some love:
-

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://ko-fi.com/semiismaili)

          
          



