HP Probook 430 G2 (Broadwell) with macOS BigSur 11.5 using OC 
============================================

- Bootloader version: Opencore 0.6.8
- macOS version: macOS Big Sur 11.5 (20G95)
![Oops!There was supposed to be an image here](https://i.imgur.com/g6x8IU9.png)

#### Hardware Specification
| Component | Specs |
|------------|----------------------------------------|
| **CPU**     | `Intel Core i3-5010U` |   
| **RAM**     | `8GB 1600MHZ DDR3L SDRAM`|   
| **HDD**     | `SSD 128GB 2.5`|
| **iGPU**    | `Intel HD Graphics 5500 `|
| **Audio**   | `Realtek ALC3227-CG`|
| **Wi-Fi**   | `Integrated Realtek RTL8161GSH-CH`|
| **OS**      | `macOS Big Sur 11.5 (20G71)`|
| **Boot**    | `OpenCore 0.6.8`|

 
#### What works
- iGPU acceleration (Intel HD Graphics 5500 1536mb)
- Sleep
- Battery Percentage
- Display Brightness
- USB ports
- Internal Camera
- Wi-FI
- Bluetooth
- Icloud
- Native Power Management/(Also with cpufriend)
- SMBus Controller
- CPU Temperature Monitoring
- iMessage
- Facetime
- Trackpad with all 14 gestures

#### What doesn't work
- Audio
- Fingerprint

#### Not tested
- HDMI output (both audio and video)

#### Benchmarks
- Geekbench 5 [Multi-core and Single core](https://browser.geekbench.com/v5/cpu/9607266)

#### Important
- In the config.plist, section `PlatformInfo > Generic`, the following fields are currently needed to change. Please generate your own serial. 

- This repo can be helpful for other HP Probook/Elitebook series notebooks since I have made 2 before with HP Elitebook 840 G7 and HP Elitebook Folio 1040 G3.
 
### BIOS Configuration

#### Enable

- Fast Boot
- Runtime Power Management
- Extended Idle Power States
- Deep Sleep
- Power Control
- Turbo Boost
- Graphic Memory Set to 64mb
- Virtualization Technology (VTx)
- Hyperthreading
- Multi Processor

 #### Disable
 
- Legacy boot
- Wake when lid is opened
- Wake on USB

#### To Fix 
- Audio
- Fan Speed Monitoring


#### Having some problem
Create an issue and I'll try to help as many as I can

#### Credits
- [Apple](https://apple.com) for [macOS](https://www.apple.com/macos/big-sur/)
- [Acidanthera](https://github.com/Acidanthera) for [OpenCorepkg](https://github.com/acidanthera/OpenCorePkg) and necessary kexts
- [reddit](https://www.reddit.com/r/hackintosh/) for it made me start many years ago and also best community for hackintosh 
- [OpenIntelWireless](https://github.com/OpenIntelWireless) for [itlwm](https://github.com/OpenIntelWireless/itlwm)
- [OpenIntelWireless](https://github.com/OpenIntelWireless) for [Heliport Intel Wi-Fi Client](https://github.com/OpenIntelWireless/HeliPort)
