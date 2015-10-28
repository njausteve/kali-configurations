# kali-configurations
This is a full guide of my dual boot intsallation on my hp spectre x360 dual boot {kali linux 2.0 and windows 10 }
    it includes 
    ;
          1.files to include in the bootable installation file containing the grub files for boot in efi secure boot 
             - just copy the EFI folder in the root of the usb bootable media containig kali 2.0
     
          2. it contains the sourcelist for repositories  to use with kali 2.0
             and are to be copy pasted in the etc/apt/sourcelist file.
            -after saving run the command     #sudo apt-get update followed by #sudo apt-get upgrade
     
          3. It also contains the lines to be edited in the grub file to make the audio work which should be followed by
              update of gub settings as indicated in the grub file.
     
          4. It also contains .deb packaged to be copied in the /root/firmware folder of the usb intallation to make     
          intwifi work  during setup.
