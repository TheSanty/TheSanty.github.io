---
layout: post
title:  "Rename Kernel v7 (sakura & Daisy)"
categories: blog
tags : [sakura,daisy]
author : SudhirYadav
---

![Rename](https://i.imgur.com/fWZqZ9S.jpg?raw=true)

**Rename Kernel** is a kernel suitable for sakura & daisy devices.
This Kernel aims to use be simple, stable and optimized!

### Changelog
2021-09-25
- Merge Linux Stable v4.9.283
- Compile with Google clang 13.0.2
- Improve Performance 
- Fix Battery High Consumption
- Fix Frequency Stats tab not available in kernel manager
- Fix lz4 compression by default in not working
- drivers/usb: Add Drivedroid Support
- cpu-boost: Reduce input boost time interval
- cpu-boost: Rework scheduling setup
- cpuidle: Allow enforcing deepest idle state selection
- remove ™ symbol from kernel name (because some app is not opening)
- and many more you can check my git.
### Notes
* Separate Build for Daisy And Sakura so download device specific.
* Checkout my new channel

### Known issues
* None

### Device info
* **Kernel** - 4.9.x
* **Chipset** - Qualcomm Snapdragon 625 MSM8953

### Telegram Group
* **Rename-Kernel** - [Join](https://t.me/RenameKernel)

### Telegram Channel
* **The Santy's Hub** - [Join](https://t.me/thesantyhub)

### Screenshots
<details>
<div id="images">
<img class="screenshot" src="https://i.imgur.com/UMaiLAD.jpg">
<img class="screenshot" src="https://i.imgur.com/YYdJ4Jd.jpg">
</div>
</details>

### Downloads
* **Github-Releases** -     [View](https://github.com/TheSanty/kernel_xiaomi_msm8953/releases)
* **Rename-Daisy-V7** -     [Download](https://github.com/TheSanty/kernel_xiaomi_msm8953/releases/download/v7/Rename-Daisy-V7.zip)
* **Rename-Sakura-V7** -     [Download](https://github.com/TheSanty/kernel_xiaomi_msm8953/releases/download/v7/Rename-Sakura-V7.zip)

### Donate
If you found this helpful, please consider supporting development 😁
How To Donate:-

* **UPI:** thesanty@indianbank
* **PayPal:** https://www.paypal.me/thesantyhub

### How to Flash ?
**Instructions**

1) Boot into custom recovery 

2) Wipe cache, dalvik

3) Flash latest build

4) Reboot your device 

### Sources
* **Kernel source** - [Click here](https://github.com/TheSanty/kernel_xiaomi_msm8953.git)
