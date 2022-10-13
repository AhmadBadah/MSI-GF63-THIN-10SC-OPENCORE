# MSI-GF63-THIN-10SC-OPENCORE
MSI GF63 10SC OpenCore 0.7.4 Monterey 12.6

Guided by: https://dortania.github.io/OpenCore-Install-Guide/

Insert your own Platforminfo in config.plist

## Configuration

| Specifications | Detail |
| ------------------- | ------------------------------------------- |
| Computer model      | GF63 Thin 10SC 15.6' (GTX 1650)      |
| Processor           | Intel Core i5-10500H Processor     |
| Memory              | 16 Gb DDR4 3200 Mhz             |
| Hard Disk           | NVMe 512 Gb    |
| Integrated Graphics | Intel UHD Graphics 2048                     |
| Monitor             | IPS FHD 1920x1080 (15.6 inch) |
| Sound Card          | Realtek Audio ALC233         |
| Wireless Card       | Intel Wireless 9560  swapped to BCM94360NG                  |
| USB                 | 1x USB type C port and 3x USB 3.2 gen 1 ports  |

## Change BIOS settings

1. Show hidden settings with: CTRL Right + SHIFT Right + ALT Left + F2
2. Turn off Secure Boot [Security]
3. Turn off CFG Lock [Advanced -> Power & Performance -> CPU -> CPU Lock Configuration]
4. Disable Fast Boot [Boot]
5. Select UEFI mode without CSM [Boot]

## Works
- Intel UHD 2048 Graphics Acceleration
- Facetime + iMessage
- Sleep/Wake
- Realtek alc233 Audio
- Trackpad with multi-touch gestures
- Battery status
- Bluetooth
- All USB Ports
- Function Key
- Bluetooth Headset Mic
- Wifi
- Handoff
- HDMI video / audio

## Disabled
- GTX1650 dGPU
