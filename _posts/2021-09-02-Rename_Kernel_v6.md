---
layout: post
title:  "Rename Kernel v6 (sakura & Daisy)"
categories: blog
tags : [sakura,daisy]
author : SudhirYadav
---

![Rename](https://i.imgur.com/fWZqZ9S.jpg?raw=true)

**Rename Kernel** is a kernel suitable for sakura & daisy devices.
This Kernel aims to use be simple, stable and optimized!

### Changelog
2021-09-02
- Merge Linux Stable v4.9.281
- Compile with Google clang 13.0.2
- Add Vibration Control
- Add Sound Control
- Add USB Fast Charging (enable by default)
- zram: use lz4 compression by default
- UPSTREAM: lib: update LZ4 compressor module
- dts: msm8953: disable coresight
- selinux: disable auditing
- trace: add CONFIG_DISABLE_TRACE_PRINTK option
### Notes
* Separate Build for Daisy And Sakura so download device specific.

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
<img class="screenshot" src="https://i.imgur.com/mbZ9Qtb.jpg">
</div>
</details>

### Downloads
* **Rename-Daisy-V6** -     [Download](https://github.com/TheSanty/kernel_xiaomi_msm8953/releases/tag/v6)
* **Rename-Sakura-V6** -     [Download](https://github.com/TheSanty/kernel_xiaomi_msm8953/releases/tag/v6)

### How to Flash ?
**Instructions**

1) Boot into custom recovery 

2) Wipe cache, dalvik

3) Flash latest build

4) Reboot your device 

### Sources
* **Kernel source** - [Click here](https://github.com/TheSanty/kernel_xiaomi_msm8953.git)
