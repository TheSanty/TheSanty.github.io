---
layout: post
title:  "Rename Kernel v3 (sakura & Daisy)"
categories: blog
tags : [sakura,daisy]
author : SudhirYadav
---

![Rename](https://i.imgur.com/fWZqZ9S.jpg?raw=true)

**Rename Kernel** is a kernel suitable for sakura & daisy devices.
This Kernel aims to use be simple, stable and optimized!

### Changelog
2021-07-21
* Merge Linux Stable 4.9.268 -4.9.276
* Add Daisy config
* Add Wireguard
* set GPU timeout 64ms
* Add Missing Frequency
* dts: pm8953: Switch to software debouncing for pon keys
* msm: kgsl: Remove debugfs directory inside lock
* msm: kgsl: Relax adreno spin idle tight loop
* msm: kgsl: Skip state change in idle check, if requested state is NONE
* scripts/Makefile.lib: speed up build process
* drm/msm/sde: Omit debug logging code
* msm: kgsl: Don't try to wait for fences that have been signaled
* defconfig: Enable CONFIG_QPNP_SMBCHARGER_D1A
* Fix Charging issue huge Thanks to **@runrunrun00**
* power: qpnp-fg-gen3: Calculate battery more linearly
* thermal: increase thermal trip to 17
* dtsi / gpu: Set powerlevel to 6
* fix sdcard issue

### Notes
* Separate Build for Daisy And Sakura so download device specific.
* For Security reason all who are on Rename Kernel 2.5 version must upgrade to latest

### Known issues
* None

### Device info
* **Kernel** - 4.9.x
* **Chipset** - Qualcomm Snapdragon 625 MSM8953

### Telegram Group
* **Rename-Kernel** - [Join](https://t.me/RenameKernel)

### Screenshots
<details>
<div id="images">
<img class="screenshot" src="https://i.imgur.com/r0MmEJT.jpg">
</div>
</details>

### Downloads
* **Rename-Daisy-V3** -     [Download](https://github.com/TheSanty/kernel_xiaomi_msm8953/releases/tag/v3.0)
* **Rename-Sakura-V3** -     [Download](https://github.com/TheSanty/kernel_xiaomi_msm8953/releases/tag/v3.0)

### How to Flash ?
**Instructions**

1) Boot into custom recovery 

2) Wipe cache, dalvik

3) Flash latest build

4) Reboot your device 

### Sources
* **Kernel source** - [Click here](https://github.com/TheSanty/kernel_xiaomi_msm8953.git)
