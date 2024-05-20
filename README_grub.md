without divas used ios install file 
o use the grml-rescueboot option:

    Install grml-rescueboot

       ***** sudo apt-get install grml-rescueboot****

    Place bootable ISO files in the /boot/grml folder.
        Since this is a system folder, the operation must be conducted as "root". For example, if the ISO is located in the user's Downloads folder, the command would be:

            ****sudo mv ~/Downloads/<filename.iso> /boot/grml/*****

    Update GRUB

       **** sudo update-grub*****
