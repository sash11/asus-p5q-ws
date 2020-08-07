macOS Catalina 10.15.6 on ASUS P5Q-WS motherboard with Core2Quad Q9650 CPU

Preparation process: DSDT.aml was taken from Clover boot-loader with F4. All errors were fixed with MaciASL 1.5.6/1.5.7. No patches were applied. Just clean DSDT.aml Some warnings remained, like:

25, 3168, Legacy Processor() keyword detected. Use Device() keyword instead.
4784, 3141, Missing dependency (Device object requires a _HID or _ADR in same scope)

Prepared USB flash drive and installed Clover and Opencore with legacy option, since there is no UEFI support in the BIOS. AHCI support is present in the BIOS though. So hard disk was recognised without the need for extra kexts.

Video card that is used during the install is EN6600GT. It is not supported, but works with a generic driver. Clover shows 3MB of memory and opencore shows 1MB. I plan to swap it for nVidia GT710 later.
