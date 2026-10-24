# Retro Console Mod Collection

一个用于**收集、记录复古游戏机改造方案**的开源资料库。

这里汇集了从任天堂 FC / Game Boy 到 PS2 / Wii 等十余个平台的硬件改造方案，涵盖视频输出改造（RGB / HDMI / S-Video）、主板复刻与硬件逆向、烧录卡与自制卡带、手柄现代化改造（蓝牙 / USB）、电源与接口改造、固件与内核备份等方向，持续更新中。

> 仓库中的改造方案大部分为 GitHub 开源项目，少部分为作者本人参考网上公开资料设计的成果，仅做收集和备份。
>
> 如果某项内容的作者不希望被收录，欢迎联系删除。

## 🗺️ 快速导航

| 平台 | 内容概要 |
| --- | --- |
| [🕹️ Famicom / NES](#user-content-fc) | 锁区解锁、FC-RGB 套件、复刻 NES、烧录卡、手柄无线化 |
| [🎮 SFC / SNES](#user-content-sfc) | RGB Bypass、全区全制式、烧录卡、锅仔片手柄、rom 工具 |
| [⚡ MD / Mega Drive](#user-content-md) | 转区改制式、Triple Bypass、Mega Amp、FeRAM 记忆卡、SM801X 复刻 |
| [👾 Game Boy](#user-content-gameboy) | 全复刻主板、反显改背光、内录机、MBC 系列烧录卡 |
| [🌈 GBP / GBC](#user-content-gbp-gbc) | 电源板复刻、主板逆向、相机卡复刻、MBC5 震动卡 |
| [📟 GBA](#user-content-gba) | 主板逆向复刻、Type-C 充电、gbaHD 内录机、ChisFlash 系列 |
| [🦢 WSC / WonderSwan](#user-content-wsc) | 硬件 wiki、内录机、复刻卡带、自制联机线 |
| [✌️ NDS / DS](#user-content-nds) | AV 输出、改 GBA（Macro）、Type-C、R4 内核备份 |
| [🔺 N64](#user-content-n64) | RGB / HDMI / DVI 改造、FPGA 进阶项目、烧录卡、FRAM 记忆卡 |
| [🪐 Saturn](#user-content-saturn) | FRAM 改造、数字音频、全区 BIOS |
| [🎛️ PCE](#user-content-pce) | RGB / S-Video 改造、主板复刻、内置蓝牙 |
| [💿 PS1](#user-content-ps1) | SD2PSX 记忆卡、PicoMemcard、数字音频 |
| [📀 PS2](#user-content-ps2) | BlueRetro 外置接收器、直读芯片大全、游戏封面 |
| [🌀 DC / Dreamcast](#user-content-dc) | 手柄转接、光驱改硬盘、HDMI 改造 |
| [🔲 NGC / GameCube](#user-content-ngc) | Xeno 直读、PicoBoot 免盘、GCVideo 系列、开源手柄 |
| [🌊 Wii](#user-content-wii) | HDMI 改造、手柄转接 |
| [⌚ GameWatch](#user-content-gamewatch) | 刷机完整教程 |
| [📺 视频转换器](#user-content-video-converter) | RGBS / VGA 转色差与 S 端子、GBSC 迷你版 |
| [🎨 Art works](#user-content-art-works) | 全机种 logo、标准贴纸底板等美术资源 |

---

## 🕹️ Famicom / NES

<a id="fc"></a>

### 本体 Mod

- NES 解锁区
  - [原贴](https://www.consolesunleashed.com/guides/nintendo-entertainment-system-region-free-mod-install-guide/)
  - [或者看这里](./FC/NES锁区解锁方法.pdf)
- FC-RGB
  - [LAVA-FC](http://www.lava-fc.top/) —— 国产 FC-RGB 套件，开发作者炸大猫 king
  - [LAVARSC LITE](./FC/LavaRSCLite.zip) —— 炸大猫开源的支持 RGB、S-video 和复合视频信号的开源 FC PCB
  - [89 版 FC 加装 LAVA 套件](./FC/89版fc改lava转接板.zip)
    - [数码之家 @hanshgq 改装 newfc 输出接口并加装 lava 套件的教程](./FC/任天堂FC89加装Lava%20FC%20RGB板，改newfc输出接口过程分享%20-%20创意DIY%20数码之家.pdf)
      - [原贴](https://www.mydigit.cn/forum.php?mod=viewthread&tid=418696&page=1)
    - [改 lava 的转接板](./FC/(红白机、NewFC、双子星)改lava转接板PCB源文件/)
- 89 版 FC 改任天堂多功能尾插
  - [DIY 尾插](./FC/diy任天堂多功能尾插.zip)
- 其他尾插
  - [有竖纹简易版](https://www.pcbway.com/project/shareproject/Famicom_AV_Power_Board_bc97a170.html)
  - [89 版尾板带音频放大](https://oshwhub.com/ayong82/fc-wei-ban)
- 复刻 NES
  - [OpenTendo](https://github.com/Redherring32/OpenTendo)
- 小天才复刻
  - [复刻小天才](https://github.com/mleonid2000/dendy_junior_remastered)
- [NES 复刻集成 RGBS 模块](https://github.com/mmoracantallops/fiNESse)
- [Type-C 电源板及 AV](https://github.com/hakkslab/FamicomPowerBoard)
- Candy 8bit
  - [全集成复刻 FC](https://github.com/HotPixelChannel/Candy_8bit/tree/main)
- [红白机工程原理图](https://oshwhub.com/ayong82/hong-bai-ji-fu-ke_copy)
- FC CIC 复刻
  - [avrciczz-ATTINY13](./FC/avrciczz-master.zip)
    - [ATTINY 固件](https://github.com/krikzz/avrciczz)
- FC / NES 蓝牙接收器
  - [BlueRetro HW1 分支](https://github.com/darthcloud/BlueRetro/wiki/BlueRetro-Cables-Build-Instructions#fc--nes-adapter-cable)

### 卡带及烧录器

- [Coolgirl-Multicart（原版 0402 容阻）](https://github.com/ClusterM/coolgirl-famicom-multicart) —— 俄罗斯作者 Cluster 的原版卡带及烧录器，使用 Diptrace 设计，容阻为 0402 封装，焊接难度较高
  - [Famicom-dumper-writer 新版烧录器 stm32+cpld](https://github.com/ClusterM/famicom-dumper-writer) —— 烧录器需要配合 [rom 生成工具](https://github.com/ClusterM/coolgirl-multirom-builder) 和 [客户端](https://github.com/ClusterM/famicom-dumper-client)
- [旧版 famicom-dumper-writer avr 版](https://github.com/ClusterM/famicom-dumper)
- [FC-kazzo 烧录卡-8MB](https://oshwhub.com/hujie888/fc_2flash_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy) —— 国内作者沐沐开源，支持 mapper45、52、176，需要使用 kazzo 烧录
- [FC-MIX-epm240 游戏卡](https://oshwhub.com/firseve/fc_mapper_240_copy)
- [mapper4 卡带](https://oshwhub.com/ayong82/fc-hong-bai-ji-mapper4-you-hu-ka-dian-lu)
- [UNROM-512 卡带 mapper30](https://oshwhub.com/sinzo/nes-cartridge)
- [NES-CN-ROM-256 mapper3 / mapper185](https://github.com/emeargt/nes-cnrom)
- [norom unrom 卡带（不支持卡带烧录）](./FC/烧录卡烧录器相关/norom%20unrom%20board/)
- [kazzo 烧录器插件版](https://oshwhub.com/ayong82/kazzo-shao-lu-qi)
- [kazzo 烧录器贴片版](https://oshwhub.com/firseve/kazzo_smd)
- [29 系 EPPROM 编程器](https://oshwhub.com/firseve/eeprom_stc_copy)

#### 卡带相关

- [原版卡带 PCB 封装](https://github.com/Gumball2415/NES-Famicom-Cartridge-Dimensions) —— 原装卡带封装，用来复刻正版卡
- [FC 60PIN 卡槽转 NES 72pin](https://github.com/veremenko-y/famicom-to-nes)

### 外设

- [手柄 15 针转 7 针 9 针双子星用](https://github.com/jeffqchen/TwinDiamond-Twin-Famicom-Expansion-to-NES-SNES-Controller-Adapter) —— FC 和双子星 15 针转两个 7 针 NES 手柄和两个 7 针 SFC 手柄
- [手柄 15 针转 7 针 9 针原版 FC 用](https://github.com/jeffqchen/FamiCoun-Famicom-Front-Expansion-NES-SNES-Adapter)
- [FC & NES 手柄改无线](https://yakaracolombia.github.io/esp32-online-tool/nes.html) —— [原理图见此](./FC/fc、nes手柄改无线/diagrama-nes-lite.jpg)
- [NES 手柄 PCB（给 C64 雅达利用的）](https://gitlab.com/nes64/NES64) —— NES controller replacement board for C64, Amiga, Atari
  - [说明](https://nes64.pryds.eu/instructions.html)
- [NES 手柄原理图](https://gamesx.com/wiki/doku.php?id=controls:nes_snes_controller)
- [NES 原理图大全](https://gamesx.com/wiki/doku.php?id=schematics:console_related_schematics)
- [NES 手柄转 USB](https://github.com/MickGyver/DaemonBite-Retro-Controllers-USB/tree/master/NESControllersUSB)
- [NES 光枪](https://boojakascha.ch/index.php?page=NESLCDgun)
- [鼠标转 NES 手柄](https://github.com/HotPixelChannel/Mouse-To-NES)

### 游戏资源及工具

- [FC & FDS & NES 精选游戏 717](./FC/FC%20&%20FDS%20&%20NES%20精选游戏%20717.zip)
- [mapper 分类工具](./FC/各种工具/MapperTools.exe)
- [旋风大佬网盘链接](http://flamecyclone.ysepan.com/)

---

## 🎮 SFC / SNES

<a id="sfc"></a>

### 本体 Mod

- [SNES RGB BYPASS MOD](https://github.com/borti4938/SNES_RGB_Bypass) —— 包括 1chip、JR 和早期 2chip 的机型改装
  - [2chip 改 rgb 模块](https://www.pcbway.com/project/shareproject/W441760ASH29_2chip_snes_rgbmod_519bcb95.html)
- [SNES_MultiRegion_with_DeJitter_QID](https://github.com/borti4938/SNES_MultiRegion_with_DeJitter_QID) —— SFC 用全区全制式模块以及去抖动
- [supercic](./SFC/supercic.zip) —— PIC12619
  - [网址](https://sd2snes.de/blog/cool-stuff/supercic)
- [SFC 原理图](./SFC/snes_schematic_color.pdf)
- [SFC JR 改 S 端子](./SFC/sfc%20jr%20改s端子.zip)
- [SFC 视频输出口 3D 复刻件](https://github.com/TRP-Retromods/SNES_AV_Connector)
- [PAL 制 SFC 复刻](https://github.com/stonedDiscord/nonSNES)
- [超任 RGBS 转 VGA 输出](https://github.com/jeffqchen/SNES2VGA)
- [机器增加手柄复位 mod](https://github.com/Nold360/lazy_mans_snes_reset)
- [SFC 蓝牙接收器 BR 分支](https://github.com/darthcloud/BlueRetro/wiki/BlueRetro-Cables-Build-Instructions#sfc--snes-adapter-cable)

### 卡带及烧录器

- [sd2snes](https://github.com/mrehkopf/sd2snes)
- [SNES 2mb flashcard Lorom/Hirom no save pcb](https://www.pcbway.com/project/shareproject/SNES_2_mb_flashcard_Lorom_Hirom_nosave_pcb_a6cb9002.html)
- **[Mousebit labs 二合一烧录卡](https://github.com/MouseBiteLabs/Super-Nintendo-Cartridges)** —— 推荐此卡，可加 LDO 更换 3V flash，复位键更换游戏，支持特殊芯片卡外所有游戏
- [Snes Flash cart by RetroCircuits](https://www.pcbway.com/project/shareproject/Snes_Flash_cart_by_RetroCircuits_dc8cc488.html)
- [SNES M27C801 HiRom 8Mib 无存档单卡 5V 片](https://www.pcbway.com/project/shareproject/SNES_M27C801_HiRom_8Mib_without_save_PCB_Single_Game_b414b148.html)
- [SNES M27C801 LoRom 8Mib 无存档单卡 5V 片](https://www.pcbway.com/project/shareproject/SNES_M27C801_LoRom_8Mib_without_save_PCB_Single_Game_b11b7da3.html)
- [SNES FlashCard Lorom/Hirom, 4mb max save pcb](https://www.pcbway.com/project/shareproject/SNES_FlashCard_Lorom_Hirom_4mb_max_save_pcb_eea1d7f7.html)
- [SNES DIP 42 Lorom/hirom 2MO max save pcb](https://www.pcbway.com/project/shareproject/SNES_DIP_42_Lorom_hirom_2MO_max_save_pcb_3727cc9f.html)
- [SNES FeRAM Cart](https://github.com/soniccd123/SNES-FeRAM-Cart)
- [通用烧录器 sanni cartreader](https://github.com/sanni/cartreader) —— 支持国产 D 卡，以及上述多种卡带烧录

### 外设

- [锅仔片手柄板](https://www.pcbway.com/project/shareproject/SNES_Controller_Tac_Switch_Mod_6247d2dd.html)
- [Super Game Boy Plus 自制 SGB](https://github.com/MouseBiteLabs/Super-Game-Boy-Plus/tree/main) —— A replacement circuit board for improving the Super Game Boy, or for creating a standalone Game Boy game for the SNES
- [SNES / SUPER FAMICOM Region free unlock pcb](https://www.pcbway.com/project/shareproject/SNES_SUPER_FAMICOM_Region_free_unlock_pcb_b60baff7.html)
- [原装双 IC 手柄 PCB](https://www.pcbway.com/project/shareproject/SNES_OEM_Controller_PCB_Replacement_a41ce13c.html)
- [SFC 手柄改无线](https://yakaracolombia.github.io/esp32-online-tool/snes.html) —— [原理图见此](./SFC/sfc手柄改无线.jpg)
- [SFC 手柄转 USB](https://github.com/MickGyver/DaemonBite-Retro-Controllers-USB/tree/master/SNESControllersUSB)
- [NES/SNES 双手柄转 USB](https://www.raphnet.net/electronique/2nes2usb/index_en.php)

### 软件、Rom 及周边

- [SFC 游戏 rom 处理工具 1](./SFC/Advanced_SNES_ROM_Utility.exe) / [SFC 游戏 rom 处理工具 2](./SFC/IpsAndSum.exe)
- [SFC 游戏老男人精选毕业包 v1.0](./SFC/SFC游戏老男人精选毕业包v1.0.zip)
- [SFC 全部 rom 分类列表](./SFC/超任游戏分类.xlsx)
- [经典 SFC 特辑杂志](./SFC/經典SFC特輯.zip)
- [SFC 官方说明书](./SFC/SNES%20Dev%20Manual.pdf)

---

## ⚡ MD / Mega Drive

<a id="md"></a>

### 本体 Mod

- [MD 转区转制式原理](https://mdpal60.net/regionmod)
  - [安装教程](https://immerhax.com/?p=386)
- [Switchless_SEGA_MasterSystem_MegaDrive](https://github.com/borti4938/Switchless_SEGA_MasterSystem_MegaDrive)
  - [教程](https://www.consolesunleashed.com/guides/sega-mega-drive-switchless-region-mod-install-guide/srsltid=AfmBOor8aeRmFNeUghGUDB7NJx2qkr_vsDF6CyV0qAYE3aI9WQ8uvczm)
- [Megadrive++](https://github.com/SukkoPera/MegaDrivePlusPlus) —— 转区、改制式、手柄复位等功能
- [md++ 简易版](https://github.com/pcm720/mdpp-r)
- [双晶振模块](https://immerhax.com/?p=386)
  - [双晶振模块教程](https://www.consolesunleashed.com/guides/sega-mega-drive-dual-frequency-oscillator-install-guide/)
- [初版 triple bypass 模块](https://github.com/db-electronics/triple-bypass-kicad) —— MD 三旁路模块，视频音频增强模块，绕过原始电路
- [Triple Bypass Version 2](https://github.com/tianfeng33/triple-bypass-Version-2) —— 在初版基础上的更新
- [Triple Bypass V2 Plus](https://github.com/zaxour/TripleBypassV2Plus) —— 在 V2 版本基础上的更新
- [Mega Amp 2.0 Pro](https://github.com/TRP-Retromods/MegaAmp2Pro) —— 音频改善模块，非常适用于一些音效差的型号
- [MD 改 S 端子](https://consolemods.org/wiki/Genesis:S-Video_Mod)
- [MD 原理图](./MD/原理图/)
- [各型号主板区别](https://consolemods.org/wiki/Genesis:Motherboard_Differences)
- [RGBS 转 VGA](https://github.com/jeffqchen/9DIN2VGA)
- [复刻世嘉 MDCD 机主板](https://github.com/Board-Folk/MegaCD-Main-BD)
- [MD 蓝牙接收器 HW1 BR 分支](https://github.com/darthcloud/BlueRetro/wiki/BlueRetro-Cables-Build-Instructions#genesis-adapter-cable)

### 卡带及烧录器

- [Genesis FeRAM Cart 芯片记忆卡 5V](https://github.com/soniccd123/Genesis-FeRAM-Cart)
- [OpenDrive-Genesis 芯片记忆卡带 3V 电平转换](https://github.com/soniccd123/OpenDrive-Genesis)
  - [上述两张卡的配套烧录器](https://github.com/soniccd123/OpenDrive-Programmer)
  - [上位机](https://github.com/soniccd123/OpenDrive-Editor)
- [简易 2 合 1 MD 卡无存档](https://oshwhub.com/firseve/md-cart_copy)
- [Sega Megadrive/Genesis, 27 芯片带存档](https://www.pcbway.com/project/shareproject/Sega_Megadrive_Genesis_4Mo_FRAM_save_repro_PCB_0d6f159b.html)
- [简易 4MB 单卡 无存档](./MD/卡带/PCB_MD短板_Final_2024-09-10.rar) —— 老男人论坛 @雷帕德安布雷拉
- [简易 4MB 单卡带存档](./MD/卡带/PCB_MD记忆版美观版_2024-09-10.rar) —— 老男人论坛 @雷帕德安布雷拉
- [乌克兰 OPEN-ED](https://github.com/krikzz/open-ed)
- [乌克兰配套烧录器 flash-kit](./MD/flashkit-master.zip)
- [简易编程器](https://oshwhub.com/firseve/stc-md-tsop56)
- [sanni cartreader](https://github.com/sanni/cartreader) —— 目前固件仅支持 MX29F1610 卡带

### 其他改装

- [SM801X 复刻 MD](https://github.com/HotPixelChannel/EHODRIVE_SM801_Sega_MD_Clone) —— 支持 RGBS 输出
- [鼠标转 MD 控制器](https://github.com/HotPixelChannel/Mouse-To-SEGA-MD)
- [MD 大 3 键手柄改无线](https://yakaracolombia.github.io/esp32-online-tool/genesis.html) —— [原理图见此](./MD/md手柄改无线.jpg)
- [SFC 手柄转 MD](https://www.raphnet.net/electronique/snes2md/index_en.php)

### 游戏资源

- [老男人精选](./MD/游戏精选/)

---

## 👾 Game Boy

<a id="gameboy"></a>

### 设备本体 Mod

- VIS_Modding 改装
  - [VIS_Game_Boy_DMG 支持原装屏幕的完全复刻](https://www.pcbway.com/project/shareproject/Replacement_PCB_for_the_original_gameboy_DMG_with_1_watt_speaker_lipo_battery_a_745f43ad.html) —— 自带反显芯片，也支持锂电池、IPS 屏幕
  - [VIS Game Boy DMG 2.0 仅支持 IPS 屏幕](https://github.com/VISmodding/VIS-DMG-2.0/)
- 原装主板复刻 Type-C DC 口
  - [Super DMG-01](https://github.com/kamicane/Super-DMG-01)
- MouseBiteLabs 改装
  - [Game Boy DMG Color](https://github.com/MouseBiteLabs/Game-Boy-DMG-Color) —— GBC 改成厚 GB，仅支持 IPS 屏幕
- 加装反显芯片改背光
  - [74hc04d 改装方案](https://www.instructables.com/Game-Boy-BivertBiversion-Moditication/)
  - [图例](./GAMEBOY/gb反显/)
  - [图文教程](https://consolemods.org/wiki/Game_Boy:Backlight_Mod)
- 内录机
  - [GBHDMI](https://github.com/Martoni/GbHdmi)
  - [USB 画面捕捉器](https://github.com/Staacks/gbinterceptor)
  - [VGA 输出](https://github.com/joeostrander/consolized-game-boy)
- 原理图
  - [DMG 厚 GB 原理图大全](./GAMEBOY/gameboy系列全原理图/) —— gekkio 贡献的全系列原理图，包含主板、屏幕驱动板、电源板、耳机板

### 卡带及烧录器

- [MBC1 电池存档卡](https://github.com/MouseBiteLabs/Game-Boy-MBC1-Cartridge)
- [MBC1 芯片存档卡-小吞](./GAMEBOY/卡带相关/ProPrj_MBC1%20%20FRAM（AM29F016）(定稿)_2024-09-28.epro)
- [原装 MBC1 改烧录卡](https://github.com/timville85/MBC1-Flash)
- [MBC1 芯片存档卡](https://github.com/ConsolesandCasks/MBC1-Jumper-Flash)
- [烧录器统一见后文 GBA 部分](#user-content-gba)
- [卡带按 mbcx 分类查询](https://gbhwdb.gekkio.fi/cartridges/)

### GB 卡带示波器

- [GBDSO](https://github.com/pyroesp/GBDSO)

### 游戏资源精选

- [老男人精选 gameboy 游戏](./GAMEBOY/GAMEBOY游戏老男人精选毕业包v1.0.zip)

### Game Boy 屏幕检测 ROM

- [240ptest](./GAMEBOY/gb240p.gb)

---

## 🌈 GBP / GBC

<a id="gbp-gbc"></a>

### 本体 Mod

- [GBP 原装屏幕改反显](./GAMEBOY/gbp反显/)
- [电源板 仅支持 IPS 版](https://github.com/Jackv-makes/SGR/)
- [GBC 改 GBP 仅支持 IPS 屏幕](https://github.com/MouseBiteLabs/Game-Boy-Pocket-Color)
- [GBC 主板复刻](https://github.com/ConsolesandCasks/Game-Boy-Pocket-Color) —— 采用 GBPC 原理图仅支持 IPS 屏
- [GBC 电源板复刻支持原装屏幕](https://github.com/ConsolesandCasks/CGB-R)
- [GBC CPU-04 主板逆向](https://github.com/nataliethenerd/CGB_ReverseEngineer)
- [CPU-E GBC 改 GBPC](https://github.com/nataliethenerd/CPU-E-MGBC)
- [系列原理图](./GAMEBOY/gameboy系列全原理图/MGB/)
- [GB 摄像头卡 WiFi 打印机](https://facelesstech.wordpress.com/2024/05/27/gameboy-wifi-printer/)
- [GBC 开关改 NDSL 式滑动开关](https://github.com/ConsolesandCasks/SwiftSwitch-GBC)
- [GBC 按键改锅仔片](https://oshpark.com/profiles/leggomyfroggo/page/3)
- [GBP 按键改锅仔片](https://oshpark.com/profiles/leggomyfroggo/page/2)
- [NDSL 卡槽改 GBC 卡槽](https://oshpark.com/profiles/leggomyfroggo/page/2)

### 卡带及烧录器

- [MBC5 震动卡合卡 5V 芯片](https://github.com/conker19to21/Game-Boy-MBC5-Rumble-Multicart) —— 需要原装 MBC5 电池存档，MouseBiteLabs 版改进
- [NekoCart](https://github.com/zephray/NekoCart-GB) —— Xilinx CPLD 模拟 MBC 芯片
- [正版卡改烧录卡各种 flash 转接板](https://github.com/JRodrigoTech/FLASH-ROM-Adapter-for-GameBoy)
- [MBC3 时钟烧录卡 5V 芯片](https://github.com/MouseBiteLabs/Game-Boy-MBC3-Cartridge) —— 电池存档 MouseBiteLabs 版
- [MBC3 时钟烧录卡 5V 芯片](https://github.com/HDR/MBC3-Flashcart) —— 芯片存档
- [MBC5 烧录卡 5V](https://github.com/HDR/MBC5-Flashcart) —— 芯片存档
- [GB 相机卡复刻](https://github.com/HDR/Gameboy-Camera-Flashcart) —— 需要原装卡芯片
- [MBC30 口袋水晶烧录卡复刻](https://github.com/HDR/MBC30-Flashcart) —— 水晶专用版型
- [白橙复刻 3V 芯片的 MBC5 震动卡](https://oshwhub.com/chrise/gameboy-mbc5-flashcart) —— 芯片存档
- [小吞复刻 3V 芯片的 MBC3 时钟卡](https://oshwhub.com/hetunzi/mbc3-ldo-sram-test4) —— 电池存档
- [小吞复刻 3V 芯片的 MBC5](./GAMEBOY/卡带相关/ProPrj_MBC5%20电池%20(ldo)定稿_2024-09-28.epro) —— 电池存档
- [Chisflash-MBC5 @mori](https://oshwhub.com/morinaka/chisflash-mbc5-gbc-shao-lu-ka) —— 支持 NDS 烧录
- [正版卡 PCB 复刻](https://github.com/HDR/NintendoPCBs)
- [GBA 卡带版型的 MBC5 卡带](https://github.com/nm3210/GB_Flashcarts)
- [烧录器见 GBA 部分](#user-content-gba)

---

## 📟 GBA

<a id="gba"></a>

### 本体 Mod

- [AGB-03 主板复刻](https://github.com/nataliethenerd/AGB_ReverseEngineer)
  - [文件](./GBA/AGB_ReverseEngineer-main.zip)
- [GBASP 原理图](./GAMEBOY/gameboy系列全原理图/AGS/)
- [GBASP 普亮复刻主板](https://oshwhub.com/morinaka/mori-de-gbasp-yuan-ji-fu-ke)
- [GBASP 改 Type-C 充电](https://github.com/thatdecade/gba-sp-usb-c)
- [GBA 按键改锅仔片](https://github.com/Zekfoo/tactileAGB)
- [GBASP 改耳机接口](https://github.com/rorosaurus/gba-sp-headphone-jack)
- [将 GBA 改成蓝牙手柄](https://github.com/Shyri/gba-bt-hid)
- [GBASP 蓝牙耳机发射器](https://github.com/bklevence/gba-sp-bt-audio-tx)
- [GBA 内录机](https://github.com/zwenergy/gbaHD)
  - [内录机 all in one](https://github.com/Zekfoo/gbaHD-AIO-Shield)
- [GBA 锂电池充电模块](https://oshwhub.com/morinaka/moripower-gba-yong-li-dian-chong-fang-mo-kuai)
- [GBA 逆向文档](https://problemkaputt.de/gbatek.htm#gbacartbackupids)

### 卡带及烧录器

- [ChisFlash 1.0 普罗米修斯](https://oshwhub.com/chisbread/chisflash-prometheus) —— 1M FRAM
  - [固件](./GBA/固件/chisflash1.0普罗米修斯.pof)
- [ChisFlash V0.1 青春版](https://oshwhub.com/chisbread/chisflash-pichu) —— 1M SRAM
  - [固件](./GBA/固件/chisflash0.1青春版.pof)
- [ChisFlash v1.1 雪拉比 时钟卡](https://oshwhub.com/chisbread/chisflash-celebi) —— 1M Flash + RTC，固件未开源
- [ChisFlash v1.2 大岩蛇 震动卡](./GBA/开源卡带pcb/chisflash1.2震动卡.epro) —— 1M FRAM + 震动，固件未开源
- [ChisFlash v1.1.1 老男人特供 flash 卡](./GBA/开源卡带pcb/老男人特供flash卡.epro)
  - [固件](./GBA/固件/ChisFlash1MFlash%20完美Flash识别固件+512Kb补丁.zip)
- [烧录器旧版 1.3gbxcart]() —— 已经过时，固件 hex 可以在 flashgbx 的文件夹中找到 cfw.hex（AVR 熔丝位设置高位熔丝是 0xda，低位是 0xaf）
- [BaconFlasher - GB/GBA 卡带 SPI 读写模块](https://oshwhub.com/chisbread/baconflasher) —— 目前正在 beta 阶段的新版烧录器
  - [配套 PC 端程序](https://github.com/ChisBread/FlashGBX)

---

## 🦢 WSC / WonderSwan

<a id="wsc"></a>

### 本体 Mod

- [WS 硬件 wiki](https://ws.nesdev.org/wiki/Main_Page)
- [awesome-wsdev](https://github.com/WonderfulToolchain/awesome-wsdev)
- [WS 内录机 SwancolorHD](https://github.com/zwenergy/swancolorHD)
- [bootfriend 改开机画面](https://wonderful.asie.pl/ws/bootfriend/)
- [Dump 原机开机动画](https://github.com/up-n-atom/wsceepdump)
- [Ext 接口转 USB](https://github.com/asiekierka/ws-extfriend)
- [Bandai2003 复刻](https://github.com/up-n-atom/Bandai2003)
- [原理图](https://github.com/RSDuck/swan_schematics) —— 更新中

### 卡带及烧录器

- [正版卡带 PCB 信息 1](https://github.com/amoibos/WonderSwan_Cartridge_List)
  - [正版卡带 PCB 信息 2](https://github.com/remy/ws-pcb-db)
- [无存档卡带复刻](https://github.com/X-death25/WonderSwan-Classic)
- [女巫卡复刻](https://github.com/up-n-atom/WonderWitch)
- [开源自烧录卡](https://github.com/RSDuck/nileswan)
- [MamaMitte 复刻](https://github.com/up-n-atom/MamaMitte)

### 外设

- [天鹅外壳 SFC 手柄](https://github.com/zwenergy/swantroller)
- [WS 自制联机线](https://github.com/zwenergy/WS-LinkC)
- [WS 自制耳机接口](https://github.com/zwenergy/wsheadphone)
  - [嘉立创版](https://oshwhub.com/duyes/tested-wonderswanheadphones-headset-adapter)
- [WSMTOOL](https://github.com/zwenergy/WSMtool) —— 耳机、串口线、联机线三合一

---

## ✌️ NDS / DS

<a id="nds"></a>

### 本体 Mod

- [NDS 增加 AV 输出原始项目](https://github.com/LostNintendoHistory/Lost-NDS-TV)
  - [图文视频教程](https://www.mundoyakara.com/2021/11/conecta-tu-nintendo-ds-lite-tu.html)
  - [olderzeus 软排线版带蓝牙手柄模块](https://www.mundoyakara.com/2021/11/las-dos-pantallas-de-nintendo-ds-lite.html)
  - [USB-C 输出 AV](https://github.com/facelesstech/gameboy_macro_tv_out_usb_c/tree/main)
  - [NDS 视频输出电阻平价版](https://facelesstech.wordpress.com/2022/12/17/gameboy-macro-tv-out-the-cheap-way/)
- [NDS 改 GBA 图文教程](https://www.mundoyakara.com/2021/10/convertir-ds-lite-roto-en-gameboy-macro.html?m=1)
  - [双屏切换](https://facelesstech.wordpress.com/2021/06/20/ds-lite-screen-switching-mod/)
- [双网卡模块](https://github.com/facelesstech/ds_lite_wifi_chip_switcher)
- [NDSILL 改单屏幕](https://www.jackvmakes.com/guides/nintendo-dsi-xl-to-gameboy-macro-xli)
- [NDSL 导电胶改锅仔片](https://facelesstech.wordpress.com/2022/07/23/ds-lite-clicky-buttons/)
- [NDSILL 改 C 口充电](https://github.com/facelesstech/gameboy_macro_xl_usb_c)
  - [2DSILL 改 C 口](https://github.com/facelesstech/dsi_dsixl_2ds_usb_c_charger_port)
- [NDSL 改 C 口](https://github.com/rorosaurus/nds-lite-usb-c)
- [NDSL 蓝牙](https://facelesstech.wordpress.com/2024/02/25/ds-lite-built-in-bluetooth/)
- [NDS 饭盒背光调节固件](https://facelesstech.wordpress.com/2022/08/03/ds-phat-adjustable-screen-brightness/)
- **[DSi 改无卡全套教程](https://spin.gyker.top/)**

### R4 相关程序、内核备份

- [GBA 烧录 chisflash 支持](./NDS/nds烧录包/gbabfv51cn.nds)
- [GB/GBC 烧录仅 chisflash-mbc5](./NDS/nds烧录包/gbcburnV4.1.nds)
- [HK 海绵宝宝卡内核](./NDS/内核/PRO版新银卡NP内核V3.02Plus.7z)
- [大宝剑（假）wood 卡、GW 蓝、ace 卡内核](./NDS/内核/GW蓝卡&CN白卡&ACE卡_Wood++V1.7(By天涯).7z)
- [炸弹人 com 卡内核](./NDS/内核/R4i-V4.2%20com去炸弹.rar)
- [DSTWO_EOS 整合](./NDS/内核/DSTWO_EOS整合版.7z)
- [DSONE&i 五合一整合包](./NDS/内核/[chn]DSONE(i)%20SDHC%20五核整合包%20V2.3%20群专版.7z)
- [DSONE&i 五合一拓展包](./NDS/内核/DSONE&i%20Loader%20in%20OpenDS%201.5【五合一V2.3用终极扩展包】.7z)

### 外设

- [震动卡](./NDS/NDSL震动卡.epro)

---

## 🔺 N64

<a id="n64"></a>

### 本体 Mod

#### N64 改 RGB、HDMI、DVI

- [最简易放大器版 N64 RGB AMP](https://github.com/TzorriMahm/N64_RGB_Amp) —— THS7374
  - [简中简面包板改 RGB](https://consolemods.org/wiki/N64:RGB_Mod_DIY_RGB_Amp) —— 也是 THS7374
- [gcvideo_lite N64 版](https://github.com/ikorb/gcvideo/tree/main/HDL/gcvideo_lite_n64)
- [borti4938 进阶版 FPGA 改 RGB 项目总览](https://github.com/borti4938/n64rgb_project_overview)
  - [1. N64Advanced](https://github.com/borti4938/n64adv_pcb)
    - [固件](https://github.com/borti4938/n64adv_fw)
    - 介绍：基于 FPGA 的数模视频模块，输出 RGB、RGsB、YPbPr，带 VI 去模糊，可视化菜单，游戏内复位，行倍增（480p / 576p）和三倍增（仅 NTSC，720p（非标准）），包括（简单）扫描线模拟
  - [2. N64Advanced2](https://github.com/borti4938/n64adv2_pcb)
    - [固件](https://github.com/borti4938/n64adv2_fw)
    - 介绍：与 N64Digital 和 UltraHDMI 相当，两者都是出色的改装套件，但这是开源的。分辨率高达 1440p，扫描线模拟，VI-Deblur，16 位模式，游戏内重置，屏幕配置菜单
  - [3. N64RGB](https://github.com/borti4938/n64rgb_pcb)
    - [固件](https://github.com/borti4938/n64rgb_fw)
    - 介绍：相对简单的 RGB 套件，VI-DeBlur 和 16 位模式可通过控制器或机械切换器切换，游戏中通过控制器重置
  - [4. N64RGB 软排线版](https://github.com/borti4938/n64rgb_flex)
  - [5. 杂项附加组件](https://github.com/borti4938/n64rgb_project_misc)
    - 介绍：
      - 过滤插件
      - 用于 N64RGBv2.1 和 N64Adv 安装的柔性 PCB
      - 适用于较旧/其他基于 CPLD 的 N64RGB 套件的电源调节器
      - 基于 THS7374 的 N64 RGB 放大器（已输出 RGB）
- [PicoDVI-N64](https://github.com/kbeckmann/PicoDVI-N64) —— 基于树莓派 Pico 的 N64 DVI 输出模块

#### NUS-004 主板原理图

- [文件](./N64/N64_NUS-004_Board_Files.zip)

#### N64 蓝牙接收器

- [BlueRetro 分支](https://github.com/darthcloud/BlueRetro/wiki/BlueRetro-Cables-Build-Instructions#nintendo-64-adapter-cable)
- [内置版软排线蓝牙模块](https://github.com/TharathielCB/BR4N64)

### 卡带相关

- [SUMMERCART64](https://github.com/Polprzewodnikowy/SummerCart64) —— TF 卡烧录卡，支持 N64DD
- [PicoCart 64](https://github.com/kbeckmann/PicoCart64)

### 配件

- [FRAM 免电池记忆卡](https://github.com/Element18592/N64-FRAM-Memory-Pak)
- [原装手柄改蓝牙](https://github.com/JPZV/BluN64-ESP32)
- [原装手柄改蓝牙飞线版](https://yakaracolombia.github.io/esp32-online-tool/n64.html)
- [开源 4M 扩展卡](https://github.com/MasonStooksbury/Open-Source-N64-Expansion-Pak)
- [OEM 4M 扩展卡](https://github.com/MasonStooksbury/OEM-N64-Expansion-Pak)
- [神游 64 自制 AV 线](https://github.com/HDR/iQue-Player-AV-Cable)
- [NGC 手柄转 N64](https://www.raphnet.net/electronique/gc_to_n64/index_en.php)

---

## 🪐 Saturn

<a id="saturn"></a>

### 本体 Mod

- [系统内存改 FRAM](https://consolemods.org/wiki/Saturn:FRAM_Mod)
- [数字音频模块](https://consolemods.org/wiki/Saturn:Digital_Audio_(SPDIF)_Mod)
- [全区 BIOS](https://github.com/nostalgic-indulgences/BIOS_Collection/tree/main)
- [土星手柄转 USB](https://www.raphnet.net/electronique/saturn_usb/index_en.php)

---

## 🎛️ PCE

<a id="pce"></a>

### 本体 Mod

- [改 RGB, S-Video, AV](https://github.com/zaxour/TurboNanza)
- [拓展口 RGB 输出](https://www.pcenginefans.com/forum/index.php?topic=8924.0)
- [拓展口 RGB 输出带 3D 外壳](https://oshpark.com/shared_projects/jqp6SYQ6)
- [手柄转 USB](https://www.raphnet.net/electronique/tgfx16_usb/index_en.php)
- [内置蓝牙 BlueRetro 安装](https://github.com/nostalgic-indulgences/BlueRetro_Internal_Installation/tree/main/NEC%20PC-Engine%20-%20CoreGrafx%20I%20%26%20II)
- [主板复刻](https://github.com/Board-Folk/PC-Engine)

---

## 💿 PS1

<a id="ps1"></a>

### 本体 Mod

- [蓝牙记忆卡](https://github.com/ChrispyNugget/BlueMemCard)
- [Pico 记忆卡](https://github.com/dangiu/PicoMemcard)
- [记忆卡读取模块](https://github.com/MakotoKurauchi/ps_memory_controller_shield)
- [SD2PSX](https://github.com/sd2psx/pcb) —— 带屏幕记忆卡
- [双晶振模块](https://github.com/L10N37/DFO-PS1-PSXTAL)
- [数字音频模块](https://consolemods.org/wiki/PS1:Digital_Audio_(SPDIF)_Mod)
- [SFC 手柄转 PSX](https://www.raphnet.net/electronique/snes_to_psx/index_en.php)

---

## 📀 PS2

<a id="ps2"></a>

### 本体 Mod

- [外置蓝牙接收器](https://github.com/Micha213/BlueRetro-PS1-2-Receiver) —— 带外壳文件
- [直读芯片大全](https://github.com/m4x10187/ps2-modchip-files)
- [游戏封面](https://github.com/xlenore/ps2-covers)

---

## 🌀 DC / Dreamcast

<a id="dc"></a>

### 本体 Mod

- [USB 手柄转 DC](https://github.com/OrangeFox86/DreamcastControllerUsbPico)
- [CDI 制作](https://github.com/arthabus/DreamcastCdiTool)
- [东芝光驱板改硬盘模块](https://github.com/pyroesp/Shiba-GD-IDE)
- [串口转 SD 卡](https://oshpark.com/profiles/Helder)
- [更换 BIOS](https://consolemods.org/wiki/Dreamcast:BIOS_Replacement_Mod)
- [DC 手柄鼠标键盘转 USB](https://www.raphnet.net/electronique/dreamcast_usb/index_en.php)
- [VGA 盒子](https://www.raphnet.net/electronique/dreamcast/images/dricas.gif)
- [DC 改 HDMI](https://github.com/citrus3000psi/DCHDMI-Hardware)
- [内置 BLUERETRO 安装](https://github.com/nostalgic-indulgences/BlueRetro_Internal_Installation/tree/main/Sega%20Dreamcast)

---

## 🔲 NGC / GameCube

<a id="ngc"></a>

### 本体 Mod

- Xeno 直读自制
  - [Xeno version 1](https://oshpark.com/profiles/jskyboo/page/3)
  - [Xeno version 2](https://github.com/gamaral/XenoGC/tree/master/hardware)
  - [Xeno version 3](https://github.com/Xyl2k/XenoGC-Clone)
  - [Xeno version 4](https://github.com/andreacampanella/XenoGC328)
  - [Xeno version 5](https://github.com/HDR/XenoGC-Flex)
- [树莓派免盘 PicoBoot](https://github.com/webhdx/PicoBoot)
- [Qoob 直读刷免盘固件](./NGC/NGC-QoobSX免盘.zip)
- [KunaiGC 免盘](https://github.com/KunaiGC/KunaiGC)
- [转区开关](https://www.gc-forever.com/wiki/index.php?title=Region_Switch)
- [SWISS](https://github.com/emukidid/swiss-gc)
- [NGC 内置蓝牙手柄接收器](https://github.com/Arthrimus/BlueRetro-HW2-GameCube)
- [NGC 阉割版数字接口 mod](./NGC/GC101DigitalPort-main.zip)

#### GCVideo

- [gcvideo_lite](https://github.com/ikorb/gcvideo/tree/main/Hardware) —— lattice cpld + cd3404，无固件更新
- [GCHDMI](https://github.com/citrus3000psi/GCVideo-Hardware-Designs/tree/master/Gamecube/DVI) —— XILINX，仅输出 HDMI，支持最新固件
- [GCDUAL](https://github.com/citrus3000psi/GCVideo-Hardware-Designs/tree/master/Gamecube/GCDual) —— XILINX + ADV7125，模拟信号、HDMI 支持，支持最新固件
- [GCPLUG](https://oshpark.com/shared_projects?search%5Bquery%5D=GCPlug+1.1&button=&search%5Bfilters%5D%5Bpcb_layers%5D%5Btwo_layer%5D=1&records_date_sort=desc&records_per_page=20) —— 尾插版 HDMI
- [GCMAX](https://dwz.mk/fii71) —— 尾插版 GCDUAL

### 配件

- [N64/SFC/FC 手柄转 NGC](https://www.raphnet.net/electronique/x2wii/index_en.php)
- [NGC 手柄转 USB](https://www.raphnet.net/electronique/gcn64_usb_adapter_gen3/index_en.php)
- [NGC 原装手柄改无线](https://yakaracolombia.github.io/esp32-online-tool/gamecube.html)
- [GameCube 记忆卡管理程序](https://github.com/suloku/gcmm) —— 可将存档文件写入实体记忆卡
- [SD2SP2 2.0 版本](https://oshwhub.com/hualazimo7/sd2sp2-2-0)
- [记忆卡版 2.0 SD 卡卡套](./NGC/记忆卡slotAB2%20SD.zip)
  - [配套 3D 打印外壳](./NGC/记忆卡卡壳3d文件.zip) —— 不完美需修剪
- [Pro 版 SD2SP2 卡套，无需拆底座版本](https://github.com/silverstee1/SD2SP2-POR-2.0-UPGRADE-PCB)
- [Cubeboot](https://github.com/OffBroadway/cubeboot) —— 可自定义开机界面或者在树莓派免盘改造后恢复开机方块动画
- [SP2 网卡 ETH2GC](https://github.com/webhdx/ETH2GC)
- [SlotA 网卡](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter)
- [开源 NGC 手柄](https://github.com/PhobGCC/PhobGCC-doc) —— 树莓派方案

### 模拟器资源

- [NGC 平台多机种模拟器](./NGC/NGC平台多机种模拟器.rar)

---

## 🌊 Wii

<a id="wii"></a>

### 本体 Mod

- [NES, SNES, N64 or Gamecube 手柄接遥控器](https://www.raphnet.net/electronique/extenmote/index_en.php#9)
- [NES2Wii](https://github.com/ClusterM/nes2wii) —— NES、SFC、PSX、MD、N64、NGC 链接 Wii 遥控器
- [wiihdmi](https://github.com/wmi-0/wiihdmi) —— GCVideo Wii 变种，飞线版
- [fujiflex](https://github.com/mackieks/fujiflex) —— Wii HDMI 软排线版

---

## ⌚ GameWatch

<a id="gamewatch"></a>

- [刷机完全教程](https://bbs.oldmantvg.net/thread-36263.htm)

---

## 📺 视频转换器

<a id="video-converter"></a>

- [RGBS 和 VGA 转色差、S 端子](https://oshwhub.com/hualazimo7/rgbs-zhuan-se-ci-s-duan-zi#5)
  - 上述转接器包含了 VGA（RGBHV）转 RGBS 中 HV 同步转 S 同步的原理图
  - 上述转色差、转 S 端子两部分电路独立，可拆开做精简模块
- [RGBS 转 VGA，GBSC 迷你版](https://github.com/mackieks/Shinobi-Scaler)

---

## 🎨 Art Works

<a id="art-works"></a>

美术 / 设计资源目录，包含：

- [FC](./Art%20works/fc/)
- [SFC](./Art%20works/sfc/)
- [全机种 logo](./Art%20works/全机种logo/)
- [标准贴纸底板](./Art%20works/标准贴纸底板/)

---

## 声明

- 本项目仅做**收集和备份**用途，改造方案大部分来自 GitHub 开源项目，少部分为作者参考网上公开资料设计的成果。
- 作者没有涉及的机器不在收录范围内。
- 如果某项内容的作者不希望被收录，欢迎联系删除。

## 参与贡献

- 欢迎在 [Issues](https://github.com/hualazimo7/retro-console-mod-collection/issues) 中补充你收藏的改造方案。
- 广大机友也可以在 [讨论区](https://github.com/hualazimo7/retro-console-mod-collection/discussions) 中发帖讨论。

如果这个仓库对你有帮助，欢迎点个 Star 支持一下。
