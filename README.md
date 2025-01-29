# openwrt-bcm6838
Openwrt experimental support for BCM6838 SoCs.

Not working, unsupported:
 * **GPON**, optical fiber support not possible
 * **Ethernet**, needs UNIMAC support
 * **WiFi**, needs PCIe support
 * GPIOs, LEDs

Working, full support:
 * **SMP**, dual core
 * **NAND**, it uses brcmnand-v5.0
 * **i2c**, brcmper-i2c
 
Tested using a Mitrastar GPT-2541GNAC with custom RAM firmwares. Bootlog: https://pastebin.com/raw/4VHEKVGN
