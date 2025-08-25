<img width="100%" src="https://github.com/Ruyue-Kinsenka/Logo_design_backup/blob/main/AviumUI/Avium_wiki_header.png" align="center">

<h1 align="center">AviumUI</h1>
<h3 align="center">Sunward wings etch freedom on the dawn.</h3>

---
**English** | [CN](README_CN.md) 

> ### Refined Android Experience

**AviumUI** is a meticulously crafted interface layer based on LineageOS/AOSP, delivering a polished "stock-Android-plus" experience. We focus on thoughtful enhancements to core functionality while preserving Android's fundamental purity and performance.

##  ✨ Design Principles

- **Essence Preservation**: Maintain Android's core integrity while refining the experience
- **Purpose-Driven Enhancements**: Only meaningful additions that solve real user needs

##  📥 Getting Started

### Supported Devices:
- Pixel 4 (flame)
- *More devices coming soon*

### Build from Source:
```bash
repo init -u https://github.com/AviumUI/android_manifest.git -b avium-15
repo sync -c -j$(nproc --all)
source build/envsetup.sh
lunch avium_{device_codename}-userdebug
m updatepackage
