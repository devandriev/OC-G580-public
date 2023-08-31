# CHANGELOG

## Update 2023-08-30:
1. Update the physical setup to feature an `Atheros AR5B93/9283` WLAN adapter, instead of an old `Broadcom BCM94313HMGB`, which is **unsupported** in **all** versions of macOS to date.
2. Add `IO80211HighSierra.kext` from the  [khronokernel's repository.](https://github.com/khronokernel/IO80211-Patches)

    ***Important note:*** *There can still be kernel panics when booting into macOS Big Sur with some USB devices plugged in. The issue was taking place in the previous commit also.*