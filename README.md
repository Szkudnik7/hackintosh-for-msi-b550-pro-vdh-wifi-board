# hackintosh-for-msi-b550-pro-vdh-wifi-board
hackintosh for msi b550 pro vdh wifi board

# Hardware
- MSI B550M PRO-VDH WIFI
- Ryzen 7 5800X
- 32GB Memory
- MSI Radeon RX 6700 XT MECH 2X 12G OC
- Intel Wireless N 3160 ([but it will also work with these cards](https://openintelwireless.github.io/itlwm/Compat.html))

# OpenCore version:
- OpenCore 1.0.6

# SMBIOS
- MacPro7,1
⚠️ Remember to generate your own SMBIOS using GenSMBIOS or OCAT.
Do NOT use the one included in this EFI.

# OS 
- macOS 26.2 Tahoe

# Kext
- AppleMCEReporterDisabler.kext
- CtlnaAHCIPort.kext
- Lilu.kext
- NootRX.kext
- NVMeFix.kext
- RealtekRTL8111.kext
- RestrictEvents.kext
- USBMap.kext
- USBToolBox.kext
- UTBDefault.kext
- VirtualSMC.kext
- itlwm.kext
- IntelBluetoothFirmware.kext
- IntelBTPatcher.kext
- BlueToolFixup.kext
  
# What working
- ✅ Wifi (Use [HeliPort App](https://github.com/OpenIntelWireless/HeliPort/releases/tag/v1.5.0}))
- ✅ Bluetooth (Like native)
- ✅ USB
- ✅ GPU
- still tested
  
# Not working
- ❌ Microphone
- [ ] Sleep not fully tested
- [ ] AirDrop / Handoff not supported (Intel WiFi)
- Still tested

  
