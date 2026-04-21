# OpenCore - Hackintosh Intel i5-10500 Gigabyte Z490 UD (With IGPU using HDMI Port)

![About this mac](/img/macinfo.png)

# Summary
This is my old config that is still in use and working that i managed to successfully installed MacOS Big Sur 11.2.3 on Gigabyte Z490 UD **with** Intel UHD Graphics 630 **using HDMI port** (**without** using any dedicated graphic cards)

# Tutorial I Followed
https://dortania.github.io/OpenCore-Install-Guide/ (Remember to update the EFI with ur own generated serial number)

# Hardware
- Processor: Intel i5-10500
- GPU: Intel IGPU
- Mobo: Gigabyte Z490 UD
- SSD: 1TB Samsung 990 Pro
- RAM: 2x32GB CORSAIR DDR4 VENGEANCE RAM 3200Mhz

# BIOS Setting
- CSM Off
- Other OS Selection
- Made CPU always boost

# Working
- [x] **WBluetooth** - Even with incomplete bluetooth patch (did not fix it in current EFI, do refer - https://dortania.github.io/OpenCore-Install-Guide/ktext.html#wifi-and-bluetooth if required to do it properly)
- [x] **Audio** - Front analog output + My Corsair ST100 Headset stand working - both input and output
- [x] **USB** - All port working (2.0, 3.0, 3.1), did not test transfer speed
- [x] **GPU** - Added AMD GPU support.
- [x] **Ethernet**
- [x] **Sleep/Wake**
- [x] **Shutdown**
- [x] **Restart**
- [ ] 
# Benchmarks

![GeekBench](/img/geekbench.png)
![Cinebench R23](/img/cb.png)
# Credits
- https://dortania.github.io/OpenCore-Install-Guide/ (For general Guidance)
- https://github.com/xingzai96/Hackintosh-Intel-i7-10700K-Gigabyte-Z490-UD (From what i forked to make my own)
- r/hackintosh paradise discord for help (TheBloke specificly helping me find my issues)
- https://github.com/georgetree/hackintosh-10700k-Gigabyte-Z490-Vision-g (For IGPU HDMI Framebuffer Patch fix)
