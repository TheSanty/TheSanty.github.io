---
layout: post
title:  "Rename Kernel v4 (sakura & Daisy)"
categories: blog
tags : [sakura,daisy]
author : SudhirYadav
---

![Rename](https://i.imgur.com/fWZqZ9S.jpg?raw=true)

**Rename Kernel** is a kernel suitable for sakura & daisy devices.
This Kernel aims to use be simple, stable and optimized!

### Changelog
2021-07-21
* Merge Linux Stable 4.9.276 - 4.9.278
* Merge tag 'LA.UM.9.6.2.r1-04800-89xx.0'
* power: Start killing wakelocks after 30s of idle
* selinux/avc: Only log denials
* kallsyms: reduce size a little on 64-bit
* drivers: power: add timeouts to wakelocks
* qpnp-fg-gen3: allow write any learned capacity
* power: qpnp-fg-gen3: Return true battery capacity
* power: qpnp-fg-gen3: Hardcode learned_cc_uah for sakura and daisy

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
* **Rename-Daisy-V4** -     [Download](https://github.com/TheSanty/kernel_xiaomi_msm8953/releases/tag/v4)
* **Rename-Sakura-V4** -     [Download](https://github.com/TheSanty/kernel_xiaomi_msm8953/releases/tag/v4)

### How to Flash ?
**Instructions**

1) Boot into custom recovery 

2) Wipe cache, dalvik

3) Flash latest build

4) Reboot your device 

### Sources
* **Kernel source** - [Click here](https://github.com/TheSanty/kernel_xiaomi_msm8953.git)
