# CHANGELOG

## Update 2023-09-05 (make sound work)
1. Add [AppleALC.kext](https://github.com/acidanthera/AppleALC)
2. Add layout-id `3` (`03000000`) to HDEF's DeviceProperties
3. Change model-id to `MacBookPro13,2`

This update makes G580's Conexant CX20590 sound card work with both internal speakers, microphone and 3.5mm jack. 
***Note:*** *Software mute check mark (System Preferences) is greyed out.*

## Update 2023-09-01 (update OpenCore)
1. Update to [OpenCore 0.9.4](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.9.4)
2. Change model id to `MacBookPro11,5`

## Update 2023-08-30: (make WiFi work)
1. Update the physical setup to feature an `Atheros AR5B93/9283` WLAN adapter, instead of an old `Broadcom BCM94313HMGB`, which is **unsupported** in **all** versions of macOS to date.
2. Add `IO80211HighSierra.kext` from the  [khronokernel's repository.](https://github.com/khronokernel/IO80211-Patches)

***Important note:*** *There can still be kernel panics when booting into macOS Big Sur with some USB devices plugged in. The issue was taking place in the previous commit also.*