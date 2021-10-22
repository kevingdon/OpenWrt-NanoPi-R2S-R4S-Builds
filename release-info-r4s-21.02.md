***OpenWRT 21.02 + Kernel 5.4 ***

Based on anaelorlinski/OpenWrt-NanoPi-R2S-R4S-Builds but only supporting R4S, turning on overclocking, using R4S-specific compiler flags and including the packages I want.

 NanoPi-R4S 

* Vanilla OpenWRT + some ImmortalWRT patches for RockChip target (avoiding the ones oopsing)
* R4S : r8168 driver for R4S (realtek) instead of kernel r8169 + r8169 firmwares package
* Overclocks all cores by ~20% (includes patch 992-* from ImmortalWRT)

!!! not tested extensively !!! use at own risk
