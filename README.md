# Dell-Percsion-T1600-OC-High-Sierra-EFI
Legacy Only  .boot using clover esp . usb flash mbr only  OPENCORE patched for Radeon 5450 
go to bios set to legacy 
set disk controller to AHCI
disable VT-X 
insttalling from clover efi should reboot the system 3 times before it fully installs then remove hard disk from desktop and connect to different desktop and apply legacy OpenCore ppatch if you want legacy .
your done 

testing this with the i3 CPU uses less power but stutters playing 4k on youtube.
for xeon CPU try a different build this is for i3,i5,i7 
system will not boot with built-in HD Graphics you need a video card 
later i will make a update for the hd3000 GPU if not buggy and add a intergrated GPU Build 
uses 60 watts on APC Load with i3 CPU 
