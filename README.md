# Lilu-and-Friends
A python script that can download and build a number of kexts.

Additional SDKs can be found [here](https://github.com/phracker/MacOSX-SDKs) if need be.

 * Copy them to */Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs* to use
 * You may need to change the `MinimumSDKVersion` in */Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Info.plist* if using Xcode 7.3+

***

## To install:

Do the following one line at a time in Terminal:

    git clone https://github.com/corpnewt/Lilu-and-Friends
    cd Lilu-and-Friends
    chmod +x Run.command
    
Then run with either `./Run.command` or by double-clicking *Run.command*

***

Currently Builds 42 kexts:

* ACPIBacklight
* ACPIBatteryManager
* ALXEthernet
* ATH9KFixup
* AirportBrcmFixup
* AppleALC
* AtherosE2200Ethernet
* AzulPatcher4600
* BCM5722D
* BT4LEContiunityFixup
* BrcmPatchRAM
* CPUFriend
* CodecCommander
* EnableLidWake
* FakePCIID
* FakeSMC
* FakeSMC (Kozlek)
* FakeSMC (Legacy)
* FakeSMC (RehabMan)
* GenericUSBXHCI
* HWSensors (FakeSMC + Plugins)
* HWSensors (Kozlek)
* HWSensors (Legacy)
* HWSensors (RehabMan)
* HibernationFixup
* IntelBacklight
* IntelMausiEthernet
* Lilu
* LiluFriend
* NightShiftUnlocker
* NoTouchID
* NullCPUPowerManagement
* RealtekRTL8100
* RealtekRTL8111
* USBInjectAll
* VirtualSMC
* VirtualSMC (All Tools)
* VoodooHDA
* VoodooI2C
* VoodooPS2Controller
* VoodooTSCSync
* WhateverGreen
