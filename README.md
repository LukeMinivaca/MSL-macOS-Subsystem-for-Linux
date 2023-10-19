# MSL-macOS-Subsystem-for-LucuzOS
This is a MSL (macOS Subsystem for LucuzOS). It's the opposite of WSL (Windows Subsystem for Linux) but is the same technology as WSL
Requirements: 
-Mac OS X 10.3 Panther or more recent
-A USB Stick with 16 GB+ or more (Formatted & Extended, Journaled)
-OCLP (OpenCore Legacy Patcher)
-8 GB of RAM
-MacBook 2003-2010 (no longer supported) instead use a MacBook or a iMac from 2014-2023

(In Mac OS X 10.3 Panther is the minimum macOS required for this MSL)
Commands for Mac OS X 10.3 Panther and Mac OS X 10.4 TIger:
'$ sudo gnu --gpt --install (LucuzOS version)'
"$ sudo --distro --gnu --gpt  --install (LucuzOS version choosed)'
Commmands for Mac OS X 10.5 Leopard and Mac OS X 10.6 Snow Leopard:

'$ sudo --gpt --gnu --install (LucuzOS version)'
'$ sudo --gpt --gnu --install (LucuzOS version choosed)'

Commands for Mac OS X 10.7 to OS X 10.9 Mavericks

'$ sudo --gpt --gnu --install_msl (LucuzOS Version)'
$ sudo --gpt apt --install (LucuzOS Version Chooser)'

Commands for OS X 10.10 Yosemite to macOS 10.13 High Sierra:

'$ sudo apt --install --gpt (LucuzOS Version)
'$ sudo apt --install --gpt (LucuzOS Chooser Version)'

Commands for macOS 10.14 Mojave to 14 Sonoma:

'$ sudo target=apple_installation apt --gpt --install (LucuzOS Version)'
'$ sudo --install --distro apt --gpt(LucuzOS Version)'


