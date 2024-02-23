# Proprietary
## Hitachi H8 based `#MAME:sealy.cpp`
**CPU:** Hitachi H8/3044 Microcontroller @ 13 MHz; Mitsubishi M30624 16-bit microcontroller @ ?

**Video:** 512x256 @ 60Hz

**Sound:** OKI MSM6295 DSP @ 100MHz

**Storage:** Fused in M30624 ?

**Others:** HY-02: Unknown DIP8 (ASIC/Rebadged E2PROM ?)

**Known Games:**
* Crazy Dou Di Zhu (疯狂斗地主)

## ADChip SE3208 based `#MAME:menghong.cpp`
**CPU:** ADChip SE3208 SoC (labelled as ADC Amazon-LF) @ 42.95454 MHz (master); HY04 (unknown DIP8, ASIC/rebadged) (security coprocessor ?)

**Video:** MagicEyes VRender0 (Built in the SE3208), 320x240 @ 60.054442 Hz

**Sound:** MagicEyes VRender0 (Built in the SE3208)

**Storage:** STMicro M59PW1282 128MBit Flash ROM ; 27C322 32Mbit EPROM

**Known Games:**
* Crazy Dou Di Zhu II (疯狂斗地主2)
* Meng Hong Lou (梦红楼)
* Lai Zi Dou Di Zhu (癞子斗地主) `#WEB:https://m.tb.cn/h.U87erNS?tk=fPJpde28uhS`

## Forerunner1s SG700 based `#MAME:sealy_fr.cpp`
**CPU:** Forerunner1s SG700 SoC ?

**Storage:** Kingston SDC4/4GB MicroSD Card

**Known Games:**

* WakuWaku Yukigassen (わくわく雪合戦)

# PC-Based
## Lenovo E591S/E581S
Rebranded Lenovo E591S/E581S thin client, sometimes with holes punched on the lid to bolt the RNG board in place.

Lenovo E580S (With Intel Celeron processors ?) variations exists, but some claims that those are bootlegs. This is yet to be confirmed.

**CPU:** Intel Atom D525 @ 1.80 GHz

**RAM:** 2GB, DDR3-800?

**SSD:** Sharetronic DOM disk, SATA, 1GB / Soliware Storage Technology DOM Disk, 4GB (other variations may exist)

**OS:** Windows XP Professional, likely pirated / Windows Embedded Standard 2009, licensing status unknown

**Others:** 
* RNG module, bolted on the lid of the case, wired to the serial port on the motherboard with ribbon cable. 4pin IDE power input. Not presented in all games.
* Security/IO module ?, a PCI card with a Xilinx Spartan FPGA and HY-04 (unknown DIP8, ASIC/rebadged) (security coprocessor ?) on it, identified as `SealyPCI_XI` device by the OS

Currently found models of security module:
* sealy101102-BYJX-V1.2 (Serial port populated or unpopulated)
* sealy110802-BYJX32-V1.0 (No serial port, No HY-04, may exist a variation with analog outputs ?)
* sealy110803-BYJX16-V2.0 (Serial port unpopulated)

It's unknown whether the security modules are interchangable.

**Known Games:**
* Tens, if not more than a hundred kinds of lazy assets swapped slots/fishing tables
* Let's Beat (炫次方) (Jubeat ripoff)
* Music Marble (音乐弹球) (Reflect Beat ripoff)
* Free Touch 3 (希力指多星3)

## Intel H81 based `#WEB:https://m.tb.cn/h.U8iANmV?tk=9PrYdeW4JHk`
**CPU:** Intel Pentium G3260 @ 3.30 GHz

**RAM:** 4GB

**SSD:** Brandless, 32GB

**OS:** Windows 8.1 Professional 64-bit, likely pirated

**Others:** 
* TP-LINK TL-WN821N USB Wi-Fi adapter

**Known Games:**
* Rushing Rhythm (节奏冲击) (SDVX ripoff)
* Qi Qu Sha Cheng (奇趣沙城) 
