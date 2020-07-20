![](https://img.shields.io/badge/complete-yes-green)
![](https://img.shields.io/badge/Latest%20supported-Catalina%2010.15.6-purple)

# Hackintosh 840
This repo contains EFI configuration, kext and many other for HP ElteBook 840 G3 laptop.

## Compatibility table

| macOS Codename | macOS Version | Support | Planned support | Stability |
| --- | --- | --- | --- | --- |
| Big Sur | 11.0 | No | Yes | N/A |
| Catalina | 10.15.6 | Yes | Yes | Full |
| Catalina | 10.15.5 | Yes | Yes | Full |

## Versions
| Version | Revision | Changelog |
| --- | --- | --- |
| 1.0 | beta1 | Fixed a lot of bugs. For more info visit the [Releases](https://github.com/GGorAA/Hackintosh-840/releases) page |
| 1.0 | alpha1 | Initial release. Only for testing purposes. |

## Working components

| Component | Component model | State |
| --- | --- | --- |
| Wifi | Intel Wireless AC 8260 | With bugs |
| Bluetooth | Intel Wireless AC 8260 | Working |
| Graphics | Intel HD Graphics 520 | Working |
| Sound | Bang&Olufsen | Working|
| Battery | N\A(Stock) | Working |
| Trackpad | Synaptics | With bugs |

## Known bugs

 - Apple TV/TV+ doesn't work
 - Wi-Fi doesn't work correct
 - Gestures on trackpad doesn't work
 - The "Charger connected" sound plays only in headphones
 
 If you want to contribute, feel free to create issues and pull requests!
 
 ## Installation
 ### Step one: create bootable USB of macOS
 
 You need a flash drive with size of 16 GB. Then make a bootable USB of macOS on another Mac machine. Borrow a real Mac, or use a Hackintosh.
 
 ### Step two: install Hackintosh
 
 Then, you need to install macOS on your EliteBook 840 G3. Just run macOS Installation, clear drive with Disk Utility, and install macOS using Install macOS option.
 
 
### Step three: postinstall

Download the postinstall .zip package from [Releases](https://github.com/GGorAA/Hackintosh-840/releases) page. Then, launch Kext Utility, and drag&drop `AppleIntelWifiV2.kext` to Kext Utility window. Wait until it finishes the process (it can ask you for your permission with administrator password prompt, just type in your password and go on), and proceed to next step.

### Step four: enjoy!

Now you can enjoy your fresh installation of macOS!
