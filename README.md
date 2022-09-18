Note - I no longer own this system, but I will attempt to keep the kexts, SSDTs 
and OpenCore up to date. I am not able to guarantee that this will boot, so you 
may need to report any issues that you might have or attempt to fix the issues 
yourself.

# hp-prodesk-600-g4-opencore
OpenCore EFI Config for the HP ProDesk 600 G4 series of systems.

## Please note: 
* The System Serial, Board Serial, SystemUUID and ROM (MAC address) in the config.plist need to be generated and populated by you.
* More information can be found here: https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#platforminfo. SMBIOS is iMac19,1.

## Tested System Configuration:
* HP ProDesk 600 G4 MT (minitower)
* CPU: Intel Core i7 8700T @ 2.4GHz
* RAM: 16GB 2400MHz DDR4
* SSD: WD SN720 256GB NVMe SSD
* GPU: Intel UHD Graphics 630

![image](https://cdn.upload.systems/uploads/luu1wudX.png)

## macOS version:
* Tested macOS version: macOS Big Sur 11.5.2
* Will also most likely work on Mojave, Catalina and Monterey.

## Working (tested):
* [x] GPU acceleration
* [x] Video encoder/decoder hardware
* [x] Ethernet
* [x] Audio (headphone/microphone jack)
* [x] Inbuilt Speakers
* [x] USB A ports (USB C port not tested)
* [x] NVMe/SATA SSD
* [x] CPU power management
* [x] FileVault2, APFS, Time Machine, SSD TRIM
* [x] OS Internet Installation, App Store, Apple TV

## Not Tested:
* iMessage, iCloud, Siri, iTunes, other services
* Hardware video encoder/decoder
* Hardware DRM
