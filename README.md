# MoonWalker V1 Wireless Network Router

---

## Description:

The MoonWalker is a Hungarian [DIY](https://en.wikipedia.org/wiki/Do_it_yourself "Wikipedia") prototype version Wireless Network Routers and includes an 802.11n MAC and baseband, a 2.4GHz radio and FEM, a 580MHz MIPS CPU, a 5-port 10/100 fast Ethernet switch. Solution for low power, low-cost, and highly integrated AP router and consumer electronic devices, the module requires only an external 3.3V power supply. It supports 802.11n operating up to 144 Mbps for 20 MHz and 300 Mbps for 40 MHz channel respectively, and IEEE 802.11b/g data rates. The module supports bridge mode and AP Client mode and Gateway mode. The high performance Module can process advanced applications effortlessly, such as routing, security and VoIP. It also includes a selection of interface to support a variety of applications, such as a USB port for accessing external storage and 3G/LTE modem. Especially in the IOT, a wide range of applications.

![](/img/logo.jpg)

---

## Specifications:

- Compliant to IEEE 802.11b/g/n.
- 2T2R mode with support for a 300Mbps PHY
data rate.
- DDR2 memory up to 1024Mb.
- Flash memory up to 256Mb.
- 4 LAN ports and 1 WAN port.
- Support USB 2.0 slave device for USB disk
and USB 3G/4G dongle and USB camera.
- Support SD card.
- Support interface: I2C, PCM,
I2S(192Kb/s, 24bits), PWM, SPI slave, UART lite,
GPIO.
- Security: WEP64/128, TKIP, AES, WPA,
WPA2, WAPI.
- Support AP/Client/Router mode.
- Power Supply Adapter: Standalone mode = DC 5V/1000mAh ; Extended mode = 5V/1500mAh

---

## Extra additionals:

- Extended mode (optional): Fan/LED Strip pinout header (if you use, increase input power to DC 5V/1500mAh)
- Reset button
- Network traffic LEDs indicators
- ICSP header (programming interface)
- USB connection interface (only debugging mode)
- SD Card storage interface
- Other pinout headers from Chip (see Chip Manual)
- Flashing mode sliding switch (V1.1)
- Power SPDT switch toggle (V1.2)
- Power sliding switch (V1.4)

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

### V1.4

- Changed power SPDT switch toggle to sliding switch
![](/img/17.jpg)

### V1.3

- Added through hole
![](/img/16.jpg)

### V1.2

- Added Power SPDT Switch toggle
![](/img/15.jpg)

### V1.1

- Added slide switch for enable easier standalone flashing/debug mode with only DC 3,3V input power (support many [flashing USB keys](https://www.aliexpress.com/wholesale?catId=0&initiative_id=SB_20200810135246&SearchText=ftdi+usb "Aliexpress")), say Thee not necessary  any more external power
- Hardware support for more performance and stability issue for the Ethernet ports (fixed random lagging network)
![](/img/14.jpg)

---

## Application block diagram:

![](/img/8.jpg)

---

## Samples:

![](/img/1.jpg)
![](/img/2.jpg)
![](/img/3.jpg)
![](/img/4.jpg)
![](/img/5.jpg)
![](/img/6.jpg)
![](/img/7.jpg)
![](/img/10.jpg)
![](/img/11.jpg)
![](/img/12.jpg)

---

## Schematic: [Download](https://github.com/drcyberg/MoonWalker_V1/blob/master/doc/moonwalker.pdf "Download")

![](/img/9.jpg)

---

## Firmwares:

### - Basic original release firmware: [Download](https://github.com/drcyberg/MoonWalker_V1/blob/master/firmwares/openwrt-19.07.4-ramips-mt76x8-moonwalker-squashfs-sysupgrade.bin "Download") or [View](https://github.com/drcyberg/MoonWalker_V1/releases "MoonWalker releases") (Changelogs: [OpenWRT 19.07.4](https://openwrt.org/releases/19.07/changelog-19.07.4 "OpenWRT 19.07.4"))

### - MoonWalker release firmware: [Download](https://github.com/drcyberg/MoonWalker_V1/blob/master/firmwares/openwrt-ramips-mt76x8-moonwalker-squashfs-sysupgrade.bin "Download") or [View](https://github.com/drcyberg/MoonWalker_V1/releases "MoonWalker releases")  
Optimized and secured for better performance and every mounth updated packages firmware. Include packages:
- [SQM (aka Smart Queue Management)](https://openwrt.org/docs/guide-user/network/traffic-shaping/sqm "SQM aka Smart Queue Management")
- [DNS over HTTPS with Dnsmasq and https-dns-proxy](https://openwrt.org/docs/guide-user/services/dns/doh_dnsmasq_https-dns-proxy "DNS over HTTPS with Dnsmasq and https-dns-proxy")
- [Ad blocking](https://openwrt.org/docs/guide-user/services/ad-blocking "Ad blocking")
- [Hungarian](https://openwrt.org/packages/pkgdata/luci-i18n-base-lang "Hungarian") language for luci web interface

![](/img/13.jpg)

---

## How to flash (Service mode): [Wiki](https://github.com/drcyberg/MoonWalker_V1/wiki/How-to-flash "How to flash")

---

## Manual (Chip): [Download](https://github.com/drcyberg/MoonWalker_V1/blob/master/doc/SkyLab_SKW92A_V1.04_datasheet.pdf "Manual")

---

## BOM (Bill Of Materials): [View](https://htmlpreview.github.io/?https://github.com/drcyberg/MoonWalker_V1/blob/master/bom/mwbom.html "View")

---

## PCB gerber file: [Download](https://github.com/drcyberg/MoonWalker_V1/blob/master/manufacturing/mw_v1_4.zip "Download")
---

## 3D models:

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
