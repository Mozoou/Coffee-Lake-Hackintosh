# Hackintosh EFI Coffee lake

![alt text](https://github.com/Mozoou/Coffee-Lake-Hackintosh/blob/master/info.png)

## How to use this EFI

- please generate `CHANGE_ME` from `config.plist` to your own generated code.
- this EFI use USBInjectAll if you want to feel real USB 3.0 you can map your USB port with [USBMap](https://github.com/corpnewt/USBMap) and change enable key from `config.plist` `Kernel > Add > USBMap.kext` and disable `Kernel > Add > USBInjectAll.kext`

## Generate SMBIOS
- TODO

## Build

| PC Specs            | Information                               |
| ------------------- | ----------------------------------------- |
| Processor           | Intel i3-8100 (4) @ 3.60GHz               |
| Integrated Graphics | Intel UHD Graphics 630, AMD Radeon RX 570 |
| CPU Cooler          | Cooler MasterLiquid ML240R RGB            |
| Motherboard         | Gigabyte Intel Z390 Aorus Elite           |
| Memory              | Adata DDR4 XPG Spectrix 2666Mhz 16GB      |
| Storage             | Samsung SSD 970 EVO M.2 250GB             |
| Wireless USB        | Archer T2U Plus                           |
| Bootloader          | OpenCore 1.0.2                            |
| Monitor             | Legion VX3276-2K-mhd                      |
| Headphone           | Logitech G435                             |

### Result:

- Shutdown ✅
- Restart ✅
- Sleep ✅
- Update OTA ✅
- Ethernet ✅
- Develop iOS App (Xcode) with Real Device (iPhone 11) ✅

### Issue

<!-- - Build in Wi-Fi Aorus Master ❌ -->