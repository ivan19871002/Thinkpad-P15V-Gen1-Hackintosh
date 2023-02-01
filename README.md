## Hardware Specs
### Basic info
Here is my Thinkpad P15V Gen1 specs:

### Specs:
- Intel(R) Core(TM) i7-10750H CPU @ 2.60GHz
- Intel(R) UHD Graphics 630
- NVIDIA® Quadro® P620
- Intel WM490 chipset
- Intel Wi-Fi® 6 AX201, 802.11ax 2x2 Wi-Fi + Bluetooth 5.1, M.2 Card
- Realtek ALC257 (0x0257)
- 16+16 Gb DDR4
- 2x M.2 2280 SSD
- Camera
- 2x USB 3.2 Gen 1 (one Always On)
- 1x USB-C 3.2 Gen 2 / Thunderbolt 3 (support data transfer, Power Delivery and DisplayPort™)
- 1x HDMI 2.0
- 1x SD card reader
- 1x Ethernet (RJ-45) Intel® I219V11
- 1x Headphone / microphone combo jack (3.5mm)

## Support
- OpenCore 0.8.8 official version
- Support macOS 13.2

## BIOS Configuration
- Config network: All Disabled
- Config Display: Thinkpad LCD / total graphics memory 512M / Disabled
- Config Thunderbot 3: Thunderbot BIOS Assist Mode  Off / security Level Display port and usb / Thunderbolt device Disabled
- Config Storage mode: AHCI (If you are in RST mode, you need to switch it to AHCI mode)
- Security Fingerprint: Predesktop Authentication Off / Security Mode normal
- Security Virtualization: Kernal DAM Protection Off / IVT ON/ VT-d ON / Enhanced Windows Bionmetric Security Off
- Security Internal Device Acess: All Off
- Boot mode: UEFI
- Security Secure Boot Off
- Security Intel SGX : Disabled
- Security Device Guard: Off

## Full Compatibility
- Boot clover with UEFI mode
- Built-in keyboard (partial function key and Num keyboard works well)
- native USB3 / USB2 ports
- AppleHDA native audio, Speakers + Internal Mic + Headphone
- Built in Camera
- Native power management
- Battery Status (Percentage can be displayed)
- Brightness control
- Backlit keyboard (Use Fn + space)
- INTEL iGPU UHD 630 1536MB Vram (DGPU has been disabled by hotpatch)
- Ethernet port
- Mac App Store works normally
- CPU SpeedStep
- Sleep + Wake
- Multitouch Touchpanel
- Wireless
- Bluetooth
- Trackpoint
- HDMI works well, 4K display not test
- ThunderBolt is not perfect,dont use for display


