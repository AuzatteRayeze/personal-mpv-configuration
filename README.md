This repository can sometimes be purged by myself sometimes just to freeup commit history that sometimes clutters it, but it will be remade with the same name right after when this does occur so it should not break any link to it that could've possibly have been made to it as long as it is not during the time before recreation.

All the files provided in here are just so I can show what I am currently using. I did not make any of the fonts, scripts, etc. myself other than the mpv.conf file itself which was informed from gathering information from the world wide web and the mpv wiki page.

Credit for those files that were not created by me goes completely towards their respective owners and creators.

# Tuned for my personal desktop (Desktop Battlestation Specifications)

Processor: AMD Ryzen 7 5800X3D 4.5GHz Boost with -30 Curve Optimizer applied All Core

Graphics Card: AMD Radeon XFX Mercury Magnetic Air 9070XT | GFXClk @~3300MHz | MEMClk Fast Timings @2814MHz(2800MHz)

Motherboard: ASUS ROG STRIX B550-F (Heavily Tweaked BIOS Settings)

RAM: G.SKILL Ripjaws 32GB (2x16GB) 4000MHz CL18 | Infinity Fabric: 2000MHz

Storage: Fantom Drives VENOM8 2TB Gen 4 M.2 NVMe | Read: 7400MB/s Write: 6900MB/s

# Monitor Specifications

Monitor: LG UltraGear Tandem OLED 280Hz | 100% SRGB, 99.5% AdobeRGB, 99.5% DCI-P3, 82% BT.2020 | VESA DisplayHDR True Black 500

Minimum Luminance: 0.0005cd/m² | Maximum Luminance: 1500cd/m² | Maxmimum Full-Frame Luminance: 600cd/m²

Signal Mode: 2560x1440 @ 280Hz 12-bit depth | Desktop Mode: 3840x2160 @ 120Hz 12-bit depth

# General Information

This configuration is being used with the latest official mpv development build (https://github.com/mpv-player/mpv/releases/tag/git-release) & the latest stable release of SmoothVideoProject (https://www.svp-team.com/).

# General Settings
**AMD Radeon Software Settings**
<img width="3838" height="2098" alt="image" src="https://github.com/user-attachments/assets/4c12bd79-0bc0-4a18-9616-35319a5d0f84" />

**SmoothVideoPlayer4 Settings**
Best Settings Utilizing SVP4 Interpolation Engine for 4K120fps playback
<img width="1054" height="1097" alt="image" src="https://github.com/user-attachments/assets/0815a9c9-bcc4-4d0a-8c21-719bb2b008a4" />

Forcing an exact multiplier leads to less CPU usage as well as less power since it is easier to compute than forcing a fixed framerate.

**Windows Graphics Settings**
<img width="1249" height="418" alt="image" src="https://github.com/user-attachments/assets/67c732ff-a55d-4d62-9bf8-37c032b9f892" />

Registry Path: Computer\HKEY_CURRENT_USER\Software\Microsoft\DirectX\UserGpuPreferences

Value Name: C:\Users\AuzatteRayeze\Documents\mpv\mpv.exe | Value Data: VRROptimizeEnable=0;AutoHDREnable=48;SwapEffectUpgradeEnable=1;SwapEffectUpgradeCache=1;GpuPreference=2

# Note
I absolutely refuse to use RIFE AI Interpolation as it is way more damaging to the original content when compared to SVP4's own interpolation methods.
RIFE AI can and will either completely destroy the real original frames or make original frames completely vanish when used.

At least with SVP4's interpolation it will keep all the original frames untouched by add its own calculated interpolated frames onto it.
The most visible artifacting to be seen with my current setup usually appears on lower quality encodes rather than higher quality encodes.
Usually in the form of either a "Halo Soap Opera Motion Effect" around characters in slower motion against a very detailed background or "Wavy Distorted Lines" around characters feet during motion on stairs.
