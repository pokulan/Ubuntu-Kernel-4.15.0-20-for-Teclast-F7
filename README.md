# Ubuntu 18.04 Kernel-4.15.0-20 for Teclast F7 or F6 Pro
## By Wojciech Zomkowski (pokulan)

### How to install:
#### - Install Ubuntu 18.04 (create bootable usb using etcher)
#### - Open terminal then type: sudo apt-get update
#### - Type command: sudo apt-get install git build-essential kernel-package fakeroot libncurses5-dev libssl-dev ccache
#### - Then type: sudo apt-get update
#### - Unzip downloaded kernel files to home directory
#### - Type in terminal (in home directory): sudo dpkg -i linux\*4.15.0-20\*.deb
#### Note: "4.15.0-20" is kernel version, change it if needed
#### - If everything install fine restart the system! 

### Teclast F7 linux boot tips:
#### - Disable Secure Boot in Secure section in BIOS
#### - Disable Fast Boot in Boot section in BIOS
#### - Use Etcher to create bootable USB

### Distros which boot fine: Ubuntu, Lubuntu, KaOS
### Distros which do not want to boot: Elementary OS, GParted, YUMI created pendrives

#### I'm waiting for my M2 SSD to check if this kernel works wih KaOS and if more distros would boot up I would check also with them. Anyway I will build custom kernel also for KaOS if this one doesn't work, because KaOS is more lightweight.

#### UPDATE!
### I received my SSD and installed Lubuntu 18.04 with this custom kernel, works awesome. I suggest you to instal KDE Plasma GUI (looks and works beautiful!). System with software (Android Studio, Gimp, DVB-t, Libre office...) use about 25GB, Windows 10 for example uses 30GB out of the box after installing all updates... ;)

### If you have any problems please write to me: wojtekzom@gmail.com
### Should works also with different linux distros, but didn't check that yet so be careful.
### Have a nice day!
