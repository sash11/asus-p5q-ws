OpenCore 0.6.3 macOS High Sierra 10.13.6 on ASUS P5Q-WS motherboard with Core2Quad Q9650 CPU and nVidia GT 710 2GB video card.

Prepared USB flash drive as you normally would for GUID partition table. Opencore duet package needs to be installed on the drive after OS is copied to it. Follow the excellent guide how to create legacy bootable USB on Dortania's site:
https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html#legacy-setup

After OS is up and running run the same procedure to put duet package on the hard drive where OS will be installed so that system will boot from the hard drive instead of the USB stick. I use PS2 keyboard, therefore a drive was included for that.

Still need to create USB kext for the specific board... I use this maching primarily as a time machine backup location for my other hackintoshes. It has an SSD for the boot drive and some HDDs that hold backup data and media library for Plex.

BIOS configuration:
Turn off Max CPU Value Limit.
That is all that's required really.

What is not working:
Sleep
Reboot
Shutdown
