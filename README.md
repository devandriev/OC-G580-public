# OC-G580-public
This repository contains the EFI needed to boot into macOS Monterey/Big Sur system or installer from Lenovo G580 Type 2189/20150 (see Lenovo support website for more hardware information).

## Supported hardware
As of beginning of year 2024, the supported hardware is changed as the author's hardware changed IRL. This means that only HD4000 graphics are supported. Intel HD 2000 video adapter is deprecated and won't get updades

## Branches
- `master` - this is the main branch of the repository, as of 17.03.2023 supports `HD4000` graphics;
- `gfx2000` - (DEPRECATED)this is the branch that will be supported and merged into the `master` branch.
- `gfx2000-legacy` - (DEPRECATED) this branch will be made legacy(i.e. fewer updates in general).

## Hardware
| Component | Model |
| :---------- | :------ | 
|CPU       |Intel®️ Core i7-3632QM @ 2.2Ghz|
|Motherboard | Lenovo G580-20150 HM76 Express|
|GPU         | (to be) Intel HD 4000 / ~~NVIDIA 710M~~ (disabled with `-wegnoegpu`) |
|RAM         | 2x8GB 1333/1600 Mhz |
|Trackpad    | Lenovo G580 ELAN PS/2 Trackpad |
|Display| Generic BOE LVDS Display, 1366x768 HD |
|Hard drives| SATA Kingston SKC600 256GB SSD\n<hr>IDE PLDS DVD-RW Drive|
|WiFi|Broadcom®️ BCM943224HMS 2.4/5GHz card|

