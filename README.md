 Dell Vostro 3590 OpenCore EFI FOR MAC SONOMA
<p align="center">
  <img src="https://i.imgur.com/t2i2ltB.png"/>
</p>

## Specifications :  

Device | Status | Details |
------------ | ------------- | ------------- | 
CPU | Working | **Intel(R) Core(TM) i5-10210U CPU @ 1.60GHz** |
Graphic | Working | Intel UHD Graphics |
SSD | Working | KINGSTON |
WiFi | Working | Intel(R) Wireless-AC 9560 |
Camera | Working | UNKNOW |
Audio | Working | Realtek ALC3204 |
Touchpad | Working | UNKNOW |
USB Ports | Working | USB is mapped |
OS | Working | MacOS 14 SONOMA |
Sleep | Working| macOS |

## Setting Up 

1. Place the EFI folder to the EFI partition

2. Generate your own SMBIOS :

- Do the following one line at a time in Terminal:
```
    git clone https://github.com/corpnewt/GenSMBIOS
    cd GenSMBIOS
    chmod +x GenSMBIOS.command
```
    
- Then run with either `python ./GenSMBIOS.command` on *nix system or by double-clicking *GenSMBIOS.command* on macOS.
On Windows `./GenSMBIOS.bat`.

- Choose *Install/Update MacSerial*.

- Then choose *Select the config.plist file* and select it from the EFI folder. 

- Now choose *Generate SMBIOS* and generate the SMBIOS by entering MacBookPro16,2

## Detail guide
[DORTANIA](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/coffee-lake-plus.html#starting-point)
