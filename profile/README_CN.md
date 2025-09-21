<img width="100%" src="https://github.com/Ruyue-Kinsenka/Logo_design_backup/blob/main/AviumUI/Avium_wiki_header.png" align="center">

<h1 align="center">AviumUI</h1>
<h3 align="center">Sunward wings etch freedom on the dawn.</h3>

---

> ### 更进一步的”Android+“体验

**AviumUI** 是基于 LineageOS/AOSP 的项目，提供优雅的「类原生增强版」体验。我们旨在提供在国内更棒的本地化，同时保持Android的纯粹本质与体验。

##  ✨  不断更新

- **本质保留**：在优化体验的同时维护Android的核心体验
- **便利强化**：不断改进 **强化体验+**：励志打造出”本地化+++“的独一档内容

##  📥  Get it！

### 支持设备：
- Pixel 4 (flame)
- OnePlus 13r/ace5 (giulia)
- Xiaomi 10s (thyme)
- Redmi K60 (mondrian) 
- *更多设备即将支持*

### 从源码构建(W.I.P)：
```bash
repo init -u https://github.com/AviumUI/android_manifest.git -b avium-15
repo sync -c -j$(nproc --all)
source build/envsetup.sh
lunch avium_{device_codename}-bp1a-userdebug
m updatepackage
