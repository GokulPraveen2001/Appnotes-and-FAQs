# Technical Reference Index
A curated, quick-access repository of critical application notes, E2E community FAQs, and engineering documentation authored/created by me during my time at Texas Instruments.

![App Notes](https://img.shields.io/badge/App%20Notes-1-blue)
![E2E FAQs](https://img.shields.io/badge/E2E%20FAQs-13-green)
![Devices](https://img.shields.io/badge/Devices-TDA4x%20Jacinto-orange)

---
## ⭐ My Authored Contributions

### Featured Application Notes & White Papers
* [SPL Boot Time Optimizations on Jacinto SoCs](https://www.ti.com/lit/ab/sbaa809/sbaa809.pdf?ts=1781501362497&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FTDA4VH-Q1) –  Guide to possible optimizations on TDA4x devices following SPL bootflow(Implementation and Perfomance Analysis included).

### High-Impact E2E Community FAQs

#### 🚀 Boot & Bootloader
* [FAQ: Enable Falcon Boot Mode on TDA4x devices](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1625944/faq-tda4vh-enable-falcon-boot-mode-in-j784s4) – Guide to implement and analyze the perfomance of Falcon boot flow.
* [FAQ: Enable custom UART for boot logs](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1547847/faq-j721s2xsomxevm-enable-other-uarts-for-boot-logs-in-spl) – Guide to enable custom UART for boot logs in SPL, UBoot, ATF, OPTEE and Linux Stage.
* [FAQ: Enable CLK-DATA and DEV-DATA for enabling UART](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1564309/faq-j784s4xevm-clk-data-and-dev-data-for-enabling-uarts) – Guide to enable the clock and power domains for each UART in R5 SPL stage.
* [FAQ: Enable SBL Combined Boot mode + App image loading from eMMC in HS200/HS400 mode](https://e2e.ti.com/support/processors-group/processors---internal/f/processors---internal-forum/1596104/faq-tda4vl-enable-sbl-combined-boot-mode-app-image-loading-from-emmc-in-hs200-hs400-mode) – Enable SBL Combined boot feature(SBL and TIFS loaded by ROM) from eMMC in higher speed modes.

#### 💾 Storage (eMMC / OSPI)
* [FAQ: Bug fixes in RTOS eMMC driver](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1490034/faq-j722sxh01evm-pdk-10-0-bugs-in-emmc-sbl-driver) – Verified solution resolving most common RTOS(SBL) eMMC driver bugs.
* [FAQ: Configure PSLC in eMMC](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1469551/faq-j784s4xevm-how-to-configure-pslc-in-emmc) – Guide to enable pSLC configuration in eMMC from both Linux and UBoot.
* [FAQ: Flashing to eMMC boot0/boot1 partition from Linux space](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1466421/faq-tda4vh-emmc-boot0-booting-from-linux-space) – Guide to flash bootloader binaries to eMMC Boot0/Boot1 partition and configure boot configuration parameters(such as partconf and bootbus register) from Linux space.
* [FAQ: Common DFU issues + Flashing to OSPI using DFU](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1490676/faq-tda4vh-ospi-flashing-using-dfu-dfu-issues) – Verified solution resolving most common dfu flashing issues + Guide to flash to OSPI flash using DFU.

#### 🔌 Connectivity & Peripherals
* [FAQ: Enable USB2.0 in UBOOT](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1515611/faq-j7200xsomxevm-enable-usb2-0-in-uboot) – Guide to enable USB2.0 feature in UBoot across TDA4x devices.
* [FAQ: Enable USXGMII + SGMII on TDA4x devices](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1658164/faq-tda4vh-q1-enable-usxgmii-sgmii-on-tda4vh) – Guide to enable USXGMII + SGMII interface(ie:Multilink SERDES configuration)simultaneously across TDA4x devices.
* [FAQ: TIMER in Capture Mode](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1575590/faq-tda4vh-timer-in-capture-mode) – Guide to enable Timer in capture mode across TDA4x devices for PWM signal capture and analysis.
* [FAQ: ECAP LINUX FEATURE ON TDA4 BOARDS](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1528975/faq-tda4vh-ecap-linux-feature-on-tda4-boards) – Guide to enable ECAP(Enhanced Capture) module in Linux for PWM signal capture and analysis.
* [FAQ: Enable TIFS traces on Wakeup UART](https://e2e.ti.com/support/processors-group/processors/f/processors-forum/1679960/tda4vl-q1-enable-tifs-traces-on-wakeup-uart-on-tda4x-boards) – Guide to enable TIFS traces on Wakeup UART on TDA4x devices.

---
_Disclaimer: This repository is a personal curation of publicly available links and documents compiled during my employment at Texas Instruments. It is maintained independently and is not officially endorsed or sponsored by Texas Instruments._
