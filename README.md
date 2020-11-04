OpenCore 0.6.3 macOS High Sierra 10.13.6 on ASUS P5Q-WS motherboard with Core2Quad Q9650 CPU and nVidia GT 710 2GB video card.

Prepare USB flash drive as you normally would for GUID partition table. Opencore duet package needs to be installed on the drive after OS is copied to it. Follow the excellent guide how to create legacy bootable USB on Dortania's site:
https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html#legacy-setup

After OS is up and running run the same procedure to put the duet package on the hard drive where OS is installed so that system will boot from the internal hard drive instead of the USB stick.

Things to do:
Still need to create USBMap.kext for this board.

BIOS configuration:
Turn off Max CPU Value Limit.

What is not working:
Sleep
Reboot
Shutdown
