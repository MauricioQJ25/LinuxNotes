Booting Flash Memory

1.- Download your favorite linux iso image

2.- Connect your flash memory

3.- Open Terminal and type the following

   $lsblk
   
   This command shows you where is your flash memory
   
4.-Unmount your device
  
  $umount /dev/sdx

5.- Flash your memory with the image with this command

  $bs=4M if=/path/to/debian-10.0.0-amd64-netinst.iso of=/dev/sdx status=progress oflag=sync

6.- Configure your Bios to boot with external flash memory
  
References:
https://linuxize.com/post/create-bootable-debian-10-usb-stick-on-linux/
