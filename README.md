# Prism Core

Prism Core is a lightweight, customized, and optimized Linux distribution derived from Ubuntu Cinnamon. It is engineered to provide a streamlined, high-performance environment tailored for content creation, media production, and gaming enthusiasts.

## 🚀 Key Features

* **Lightweight Optimization:** Stripped of unnecessary bloatware and background services to maximize system resource efficiency.
* **Content Creation Suite:** Pre-configured with essential production tools including **OBS Studio**, **GIMP**, and **Kdenlive**.
* **Gaming & Management:** Integrated with **Lutris** to streamline game library management from the first boot.
* **Modern Identity:** Features a customized system identity (`id_like = debian`) and an optimized Fastfetch configuration.
* **Automated Deployment:** Supports unattended installations via custom cloud-init configurations (`user-data`).

## 🛠️ Build & Compilation Details

Prism Core is built using reproducible open-source tooling:
* **Builder:** Cubic (Custom Ubuntu ISO Creator) running within a secure chroot environment.
* **Compression:** Compiled using high-ratio **xz (LZMA2)** compression to optimize image size (~5.4 GB final ISO footprint).
* **Base OS:** Ubuntu Cinnamon with a hardened and cleaned package tree.

## 📦 Installation

1. Download the latest `Prism Core` ISO release from the [Releases](../../releases) page.
2. Flash the ISO onto a USB storage drive using a multi-boot tool like **Ventoy**.
3. Boot from the USB drive and let the automated installer handle the setup process.

---
Developed by [AitorPro](https://github.com/AitorPro).
