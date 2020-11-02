# hackintosh-gigabyte-ax370

OpenCore configuration for Ryzen hackintosh

## Specification

Type|Item
:----|:----
**CPU** | [AMD Ryzen 5 1600 3.2 GHz 6-Core Processor](https://uk.pcpartpicker.com/product/mV98TW/amd-ryzen-5-1600-32ghz-6-core-processor-yd1600bbaebox)
**Motherboard** | [Gigabyte GA-AX370-Gaming K5 ATX AM4 Motherboard](https://uk.pcpartpicker.com/product/xQQRsY/gigabyte-ga-ax370-gaming-k5-atx-am4-motherboard-ga-ax370-gaming-k5)
**Memory** | [Corsair Vengeance LPX 24 GB (2 x 8 GB + 2 x 4 GB) DDR4-2400 Memory](https://uk.pcpartpicker.com/product/y9rcCJ/corsair-memory-cmk16gx4m2a2400c16)
**Video Card** | [Gigabyte Radeon RX VEGA 64 8GB Video Card](https://uk.pcpartpicker.com/product/gqTrxr/gigabyte-radeon-rx-vega-64-8gb-video-card-gv-rxvega64-8gd-b)
**Storage** | [Samsung 970 Evo Plus 1 TB M.2-2280 NVME SSD](https://uk.pcpartpicker.com/product/Zxw7YJ/samsung-970-evo-plus-1-tb-m2-2280-nvme-solid-state-drive-mz-v7s1t0bam) <br> [SanDisk SSD PLUS 240 GB SSD](https://uk.pcpartpicker.com/product/BNGj4D/sandisk-internal-hard-drive-sdssda240gg25) <br> [Kingston SSDNow V300 Series 120 GB SSD](https://uk.pcpartpicker.com/product/rtzv6h/kingston-internal-hard-drive-sv300s37a120g) <br> 2x [Western Digital Caviar Blue 1 TB 7200RPM HDD](https://uk.pcpartpicker.com/product/MwW9TW/western-digital-internal-hard-drive-wd10ezex)

[PCPartPicker Part List](https://uk.pcpartpicker.com/list/9dp7TJ)

## Config

OpenCore version 0.6.2

### Kexts

Name|Version|Description
:----|:----|:----
`Lilu.kext` | [1.4.8](https://github.com/acidanthera/Lilu/releases/tag/1.4.8) | Patches processes, required for many kexts to work.
`VirtualSMC.kext` | [1.1.7](https://github.com/acidanthera/VirtualSMC/releases/tag/1.1.7) | Emulates SMC chip found on real macs. Not using any plugins.
`AppleALC.kext` | [1.5.3](https://github.com/acidanthera/AppleALC/releases/tag/1.5.3) | AppleHDA patching to support on-board sound controller. This motherboard uses the Realtek ALC1220 codec. Using layout id 28.
