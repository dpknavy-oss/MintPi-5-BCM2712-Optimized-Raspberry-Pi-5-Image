# MintPi-5 (BCM2712 Edition)

A high-performance Linux Mint-based build optimized specifically for the Raspberry Pi 5.

## ⚠️ Hardware Compatibility
This image is **bare-metal only**. It is compiled using a 16KB memory page size native to the BCM2712 processor (Raspberry Pi 5). 

* **Supported:** Raspberry Pi 5 (BCM2712)
* **NOT Supported:** Raspberry Pi 4, 3, Zero, or any other ARM hardware.
* **NOT Supported:** Virtual Machines (QEMU/KVM, Proxmox, VirtualBox). Attempting to run this in a VM will result in an immediate kernel panic/black screen.

## 🚀 Features
* Full Mint-style desktop interface pre-installed.
* Optimized for the Pi 5's ARM64 architecture.
* Stripped of unnecessary bloat for maximum performance.

## 💾 How to Install
1. **Download:** Grab the latest `.img.xz` file from the [Releases](https://github.com/YOUR_USERNAME/MintPi-5/releases) section.
2. **Extract:** Unzip the `.xz` file to get the raw `.img` file.
3. **Flash:** Use **Raspberry Pi Imager** or **BalenaEtcher** to flash the `.img` file directly to your MicroSD or NVMe drive.
4. **Boot:** Insert into your Raspberry Pi 5 and power on.

## 🛠️ Build Information
This is a high-performance build intended for users who want a custom desktop experience on physical Pi 5 hardware.
