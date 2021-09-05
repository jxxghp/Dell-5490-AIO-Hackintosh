# DELL Inspiron 5490 AIO Hackintosh
EFI for Dell Inspiron 5490 AIO on OpenCore bootloader

### Specs:
Type | Details
| -------------- |:----------------------------:|
CPU | i5-10210U
iGPU | Intel UHD 620
dGPU | NVIDIA GeForce MX110
Display | 1920x1080
RAM | 8GB
Audio | Realtek ALC247
WLAN | Intel 9462AC
LAN | Realtek RTL8168/8111/8112
NVMe | KBG40ZNS512G NVMe KIOXIA 512GB
SMBIOS | MacBookPro 15,2
Bootloader | OpenCore 0.5.9
###### *version this is made from

### What works and What doesn't or WIP:
- [x] Intel UHD 620 iGPU eDP Output (with Backlight)
- [x] Intel UHD 620 iGPU HDMI Output
- [x] ALC3204/236 Internal Speakers
- [x] ALC3204/236 Native Jack Output
- [x] ALC3204/236 HDMI Audio Output
- [x] All USB Ports Type A
- [x] SpeedStep / Sleep / Wake
- [x] Intel Bluetooth Module
- [x] Realtek RTL8169 LAN
- [x] USB Cardreader
- [x] ACPI Battery
- [x] NVRAM
- [x] Wi-Fi
- [x] Internal Mic and Camera

- [ ] MX110 dGPU (Not supported)

## Important Notes:
- This is a **Work in Progress [WIP]**.
- Do not COPY & PASTE this and use on your installer or Mac disk's EFI Partition. This is to give you idea on what will work and a jump start to hackintosh this laptop.
- SMBIOS information are reset to default values... Apply your generated SMBIOS.
- All guides and very much needed information can be read in [Dortania's Guide](https://dortania.github.io/vanilla-laptop-guide/ "Overview - Dortania").

- Fixes for current problems are appreciated.

## To-do after installation:
* Generate your SMBIOS and put info in the 'Generic' part of config.plist.

## Changelog
<details>
<summary>Read Changelog...</summary>
  <h4> 06/11/20 </h4>
  <ul>
    <li>Changed AAPL,ig-platform-id and device-id to 0x3EA50000 to fix kernel panic at 10.15.5.</li>
  </ul>
  <h4> 06/09/20 </h4>
  <ul>
    <li>First release. Repository created.</li>
  </ul>
</details>

## Credits
- [Apple](https://apple.com) for macOS;
- [@R3TLIX](https://github.com/R3TLIX) for inspiration;
- [MoZyo](https://github.com/MoZyo) for development;
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
