# Ubuntu 18.04 Kernel-4.15.0-20 for Teclast F7 or F6 Pro
## By Wojciech Zomkowski (pokulan)

### How to install:
#### - Install Ubuntu 18.04 (create bootable usb using etcher)
#### - Open terminal then type: sudo apt-get update
#### - Type command: sudo apt-get build-dep linux-image-$(uname -r)
#### - Unzip downloaded kernel files to home directory
#### - Type in terminal (in home directory): sudo dpkg -i linux\*4.15.0-20\*.deb
#### Note: "4.15.0-20" is kernel version, change it if needed
#### - If everything install fine restart the system! 

### Teclast F7 linux boot tips:
#### - Disable Secure Boot in Secure section in BIOS
#### - Disable Fast Boot in Boot section in BIOS
#### - Use Etcher to create bootable USB

### Distros which boot fine: Ubuntu, KaOS
### Distros which do not want to boot: Elementary OS, GParted, YUMI created pendrives
#### I'm waiting for my M2 SSD to check if this kernel works wih KaOS and if more distros would boot up I would check also with them. Anyway I will build custom kernel also for KaOS if this one doesn't work, because KaOS is more lightweight.

### If you have any problems please write to me: wojtekzom@gmail.com
### Should works also with different linux distros, but didn't check that yet so be careful.
### Have a nice day!
