# B365M-ITX-ac-i7-8086K-OpenCore

99.99% perfect Hackintosh OpenCore configuration.

## Hardware
Motherboard: ASRock B365M-ITX/ac  
CPU: Intel Core i7-8086K @ 4.0GHz (6 cores, 12 threads)  
RAM: Kingston DDR4 2666MHz 16GB * 2 - Total 32GB  
iGPU: Intel UHD Graphics 630  
dGPU：N/A  
Audio: Realtek ALC887  
SSD：Intel NVMe SSD 7600P 1TB  
Ethernet: Intel I219V2 PCI Express Gigabit Ethernet  
Wi-Fi/Bluetooth：Broadcom BCM94352Z (DW1560)

P.S. : The original onboard wireless card is Intel 3168NGW, which is completely compatible with **AirportItlwm**. I used to use it so I’ve bundled AirportItlwm in the kexts. You have to enable it if you want to use it. 

## Perfectness Summary

Currently working perfectly with macOS Big Sur 11.6.

- [x] ALL hardware components perfectly WORK!
- [x] Video-Out pin injected
- [x] USB customized
- [x] Native NVRAM r/w
- [x] Sidecar / AirDrop fully enabled
- [x] No issues when SIP is fully enabled
- [x] Full featured Recovery HD
- [x] FileVault supported
- [x] Apple cloud services run well
- [ ] Still able to identify that it’s a Hackintosh via `kextstat` (Just a joke, no solution huh)

## Attention

The version of OpenCore is `0.7.4`.

Please use SMBIOS `Macmini8,1`, which is removed from config.

The config is modified based on [DalianSky](https://blog.daliansky.net)’s Coffee Lake basic config, and credit for the theme too.

Screenshot: 
![Screenshot](https://static.imvictor.tech/wp-content/uploads/2021/10/Hackintosh-Screenshot.jpg)

Blog post: [年轻人的第一台 ITX – Victor’s Blog](https://blog.qwq.ren/posts/first-itx/)