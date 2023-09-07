# len-G580-hacOS-Monterey
This repository contains the EFI needed to boot into macOS Monterey/Big Sur system or installer from Lenovo G580 Type 2189/20150 (see Lenovo support website for more hardware information).

## Supported hardware
As of 7th September 2023 this repository contains the EFI for `Intel® Pentium B960` SnB Processor with `Intel® HD2000 (2nd Gen)` graphics.

## Branches
- `master` - this is the main branch of the repository, as of 07.09.2023 supports `HD2000` graphics;
- `gfx4000` - this is the branch that will be supported and merged into the `master` branch.
- `gfx2000-legacy` - this branch will be made legacy(i.e. fewer updates in general).

## Hardware
| Component | Model |
| :---------- | :------ | 
|CPU       |Intel Pentium B860 @ 2.2GHz|
|Motherboard | Lenovo G580-20150 HM76 Express|
|GPU         | (to be) Intel HD 2000 / ~~NVIDIA 710M~~ (disabled with `-wegnoegpu`) |
|RAM         | 2x8GB 1333/1600 Mhz |
|Trackpad    | Lenovo G580 ELAN PS/2 Trackpad |
|Display|Generic BOE LVDS Display, 1366x768 HD|
|Hard drives| SATA Kingston SKC600 256GB SSD\n<hr>IDE PLDS DVD-RW Drive|

