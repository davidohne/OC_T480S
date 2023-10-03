# OC_T480S
- Open Core EFI for Lenovo T480S
- Running macOS Ventura 13.6 at the moment

# Important Remarks about this EFI
- I'm using a Dell DW1820A wifi card,
- Therefore I'm using the BrcmBluetoothInjector.kext, BrcmFirmwareData.kext, BrcmPatchRAM3.kext, AirportBrcmFixup.kext, BlueToolFixup.kext to make Bluetooth and Wifi work
- I've you are using standard Intel Wifi card you have to remove these kext's and add e.g. AirportItlwm.kext

# Copy & Paste
- Don't forget to add a generated SMBIOS into config.plist
- At this time MLB, ROM, SystemSerialNumber and SystemUUID are empty and have to be filled
- Use corpnewt/GenSMBIOS to generate a MacBookPro15,2 SMBIOS 
