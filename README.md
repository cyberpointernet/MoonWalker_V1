# MoonWalker V1 Wireless Network Router

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/drcyberg/MoonWalker_V1)](https://github.com/drcyberg/MoonWalker_V1/releases/tag/V1.4)  [![GitHub](https://img.shields.io/github/license/drcyberg/MoonWalker_V1)](https://github.com/drcyberg/MoonWalker_V1/blob/master/LICENSE)  [![GitHub release (by tag)](https://img.shields.io/github/downloads/drcyberg/MoonWalker_V1/V1.4/total)](https://github.com/drcyberg/MoonWalker_V1/archive/master.zip)  [![Website](https://img.shields.io/website?up_message=MoonWalker_V1&url=https%3A%2F%2Fdrcyberg.github.io%2FMoonWalker_V1%2F)](https://drcyberg.github.io/MoonWalker_V1/)  [![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)](https://github.com/drcyberg?tab=repositories)  [![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://github.com/drcyberg)  [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/Kunee82)  [![GitHub followers](https://img.shields.io/github/followers/drcyberg?style=social)](https://github.com/drcyberg?tab=followers)

---

## Description:

The MoonWalker is a Hungarian [DIY](https://en.wikipedia.org/wiki/Do_it_yourself "Wikipedia") prototype version Wireless Network Routers (based on Skylab SKW92A) and includes an 802.11n MAC and baseband, a 2.4GHz radio and FEM, a 580MHz MIPS CPU, a 5-port 10/100 fast Ethernet switch. Solution for low power, low-cost, and highly integrated AP router and consumer electronic devices, the SoM module requires only an external 3.3V power supply, the PCB requires only an external 6V power supply . It supports 802.11n operating up to 144 Mbps for 20 MHz and 300 Mbps for 40 MHz channel respectively, and IEEE 802.11b/g data rates. The module supports bridge mode and AP Client mode and Gateway mode. The high performance Module can process advanced applications effortlessly, such as routing, security and VoIP. It also includes a selection of interface to support a variety of applications, such as a USB port for accessing external storage and 3G/LTE modem. Especially in the IOT, a wide range of applications.

![](/img/logo.jpg)

---

## Specifications:

- Compliant to IEEE 802.11b/g/n
- 2T2R mode with support for a 300Mbps PHY data rate
- DDR2 memory up to 1024Mb
- Flash memory up to 256Mb
- 4 LAN ports and 1 WAN port
- Support USB 2.0 slave device for USB disk
and USB 3G/4G dongle and USB camera
- Support SD card
- Support interface: I2C, PCM, I2S (192Kb/s, 24bits), PWM, SPI slave, UART lite, GPIO
- Security: WEP64/128, TKIP, AES, WPA, WPA2, WAPI
- Support AP/Client/Router mode
- RoHS compliance meets environment-friendly requirement
- Power Supply Adapter: Standalone mode = DC 6V 1000mAh ; Extended mode = 6V 1500mAh

---

## Extra Additionals:

- Extended mode (optional): Fan/PWM/LED Strip pinout header (if you use, increase input power to DC 5V/1500mAh)
- Reset button
- DC Jack socket
- Network traffic LEDs indicators
- ICSP pinout header (programming interface)
- USB connection interface (only debugging mode), and support USB slave devices for USB disk and USB 3G/4G dongle and USB camera
- SD Card storage interface
- Other pinout headers from Chip
- Flashing/Debugging (USB) mode sliding switch
- Power SPDT switch toggle
- Power sliding switch
- PWM pinout header (GPIO#19)

---

## Applications:

- [x] USB WiFi Camera
- [x] IOT (internet of things)
- [x] WiFi AP
- [x] 3G/4G WiFi Router
- [x] WiFi Repeater
- [x] Building Automation
- [x] Home Automation
- [x] Smart Home Gateway
- [x] Industry Control

---

## Changelogs:

### V1.0

- First stable release

---

## Application block diagram:

![](/img/8.jpg)

---

## Samples:

![](/img/samples.jpg)

---

## Firmwares:

### - Basic original release firmware: [Download](https://github.com/drcyberg/MoonWalker_V1/blob/master/firmwares/openwrt-19.07.4-ramips-mt76x8-moonwalker-squashfs-sysupgrade.bin "Download") or [View](https://github.com/drcyberg/MoonWalker_V1/releases "MoonWalker releases")  
Changelogs: [OpenWRT 19.07.4](https://openwrt.org/releases/19.07/changelog-19.07.4 "OpenWRT 19.07.4")

### - MoonWalker release firmware: [Download](https://github.com/drcyberg/MoonWalker_V1/blob/master/firmwares/openwrt-ramips-mt76x8-moonwalker-squashfs-sysupgrade.bin "Download") or [View](https://github.com/drcyberg/MoonWalker_V1/releases "MoonWalker releases")  
Based on [OpenWRT Development Snapshot builds](https://openwrt.org/releases/snapshot "OpenWRT Development Snapshot builds") version and optimized performance for fast networks and secured for better fast internet surfing. Every mounth updated packages in firmware. Include packages:
- [SQM (aka Smart Queue Management)](https://openwrt.org/docs/guide-user/network/traffic-shaping/sqm "SQM aka Smart Queue Management")
- [DNS over HTTPS with Dnsmasq and https-dns-proxy](https://openwrt.org/docs/guide-user/services/dns/doh_dnsmasq_https-dns-proxy "DNS over HTTPS with Dnsmasq and https-dns-proxy")
- [Ad blocking](https://openwrt.org/docs/guide-user/services/ad-blocking "Ad blocking")
- [Hungarian](https://openwrt.org/packages/pkgdata/luci-i18n-base-lang "Hungarian") language for luci web interface

![](/img/13.jpg)

---

## How to flash (Service mode): [Wiki](https://github.com/drcyberg/MoonWalker_V1/wiki/How-to-flash "How to flash")

---

## BOM (Bill Of Materials): [View](https://htmlpreview.github.io/?https://github.com/drcyberg/MoonWalker_V1/blob/master/bom/mwbom.html "View")

---

## PCB gerber file: [Download](https://github.com/drcyberg/MoonWalker_V1/blob/master/manufacturing/mw_v1_4.zip "Download")

- Dimensions: 100x100mm
- Layers: 2lv

---

## 3D models:

![](/img/moonwalker.gif)
![](/img/MoonWalker.jpg)

- [Base](https://github.com/drcyberg/MoonWalker_V1/blob/master/stl/moonwalker_base.stl "Base")
- [Frame](https://github.com/drcyberg/MoonWalker_V1/blob/master/stl/moonwalker_frame.stl "Frame")
- [Simple Top Cover](https://github.com/drcyberg/MoonWalker_V1/blob/master/stl/moonwalker_top_cover.stl "Simple cover")
- [Stand](https://github.com/drcyberg/MoonWalker_V1/blob/master/stl/moonwalker_stand.stl "Stand")
- [Cover With 16x2 Lcd](https://github.com/drcyberg/MoonWalker_V1/blob/master/stl/moonwalker_top_wo_fan_16x2.stl "Cover With 16x2 Lcd")
- [Cover With 20x4 Lcd](https://github.com/drcyberg/MoonWalker_V1/blob/master/stl/moonwalker_top_wo_fan_20x4.stl "Cover With 20x4 Lcd")

## Required other parts:

- 4x M4 60mm screw
- 4x M4 nut

---

## Buy: !!!Coming soon!!!

---

## Thingiverse: [Link](https://www.thingiverse.com/thing:4262740 "Link")

---

## OpenWrt forum: [Link](https://forum.openwrt.org/t/prototype-lulo-pro-v1-wireless-network-router/60118 "Link")

---

## If you want to support me: [Donate](https://www.paypal.me/Kunee82 "Donate")

---

## Have a nice day!
