# Meshtastic-Rugged
Custom Meshtastic Node Designed for Rugged/Tactical Applications. This design is purely based on open-sourced resources and is not intended for sale

## Infrastructure
The unit is a Raspberry Pi–based MANET (Mobile Ad-Hoc Network) radio built on Wi-Fi HaLow (802.11ah). The goal is to support 802.11s mesh + batman-adv, GPS-driven range testing, and a PTT app, aiming for a rugged, field-ready kit. The project currently targets the Seeed HaLow HAT; support for other devices will be added over time. 

## Parts List
| Part Number  | Description | Quantity |
| ------------- | ------------- | ------------- |
| 1457K1601BK | Aluminum Enclosure | 1x |
| 5035 | Lithium Ion Battery (10Ah) | 1x |
| CSH-SGFB-100-UFFR | RF Cable Assy | 1x |
| _ | [MESHTAC Gooseneck Tactical Antenna 915MHz](https://store.rokland.com/products/meshtac-gooseneck-tactical-antenna-4-dbi-gain-sma-male-915-mhz-flexible-for-meshtastic-lora?srsltid=AfmBOopdveQo90jxFJhQkgTv-OG2xH585ynMQ31JdaSO8STukaQ22utp) | 1-2x |
| 109990565 | Wio-WM6108 Wi-Fi HaLow mini-PCIe Module | 1x |
| B0G3PJ1VNL | [U94 PTT Adapter to Type-C](https://a.co/d/059k1a5k) | 1x |


# OpenMANET References
## Website & Docs
- 🌐 Website: **[openmanet.net](https://openmanet.net/)**
- 📚 Docs (GitHub Pages): **[openmanet.github.io/docs](https://openmanet.github.io/docs/)**
  - 🧩 Firmware & releases: **[firmware](https://openmanet.github.io/docs/firmware)**
  - 🚀 Initial setup: **[initial-setup.html](https://openmanet.github.io/docs/initial-setup.html)**
  - 🧰 Hardware: **[hardware](https://openmanet.github.io/docs/hardware)**
  - 🕸️ Networking: **[networking](https://openmanet.github.io/docs/networking)**
  - 🛠️ Troubleshooting: **[troubleshooting](https://openmanet.github.io/docs/troubleshooting)**
  - 📡 Range testing: **[range-testing.html](https://openmanet.github.io/docs/range-testing.html)**
  - ✈️ ADS-B to CoT: **[adsb-to-cot](https://openmanet.github.io/docs/adsb-to-cot)**

## Downloads
- 📦 Releases (images): **[github.com/OpenMANET/firmware/releases](https://github.com/OpenMANET/firmware/releases)**

# PTT Options
Push-to-talk (PTT) capability is a core requirement of this application because it enables reliable voice communication over local, infrastructure-independent mesh networks. Mirroring military/LE environments, touchscreen-based interaction is often impractical due to movement, gloves, or limited visibility, making a physical PTT control essential for safe and intentional transmission. PTT reduces bandwidth contention and improves intelligibility on constrained or long-range links compared to always-on or full-duplex voice systems. By transmitting audio only while a button is actively pressed, PTT minimizes background noise and prevents accidental or unintended broadcasts. This interaction model aligns with established radio and dispatch communication practices, reducing user training overhead and cognitive load. Supporting external hardware PTT inputs (such as wired headsets or USB-C accessories) ensures the application remains usable in real-world, non-ideal operating conditions without reliance on cloud services or cellular connectivity.
## Recommended: ATAK
The Android Team Awareness Kit (ATAK), for civilian use, or Android Tactical Assault Kit (also ATAK) for military use - is a suite of software that provides geospatial information and allows user collaboration over geography.
- Link to information about CivTAK/ATAK: https://www.civtak.org/
- Link to CivTAK documentation: https://www.civtak.org/documentation/
- Android Application Download Link: https://play.google.com/store/apps/details?id=com.atakmap.app.civ

## Alternate: Mumble
Mumble is a free, open source, low latency, high quality voice chat application
- Link to information about Mumble: https://www.mumble.info/

