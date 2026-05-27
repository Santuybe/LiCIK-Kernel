# LiCIK Kernel

**LiCIK** (Lightweight CI Kernel) provides highly optimized Android kernel builds for Xiaomi and Samsung devices, integrated with advanced security features and performance enhancements.

---

## 📱 Supported Devices

| Device Name | Codename | Platform | Android Version |
| :--- | :--- | :--- | :--- |
| **Poco X3 NFC** | `surya` | Snapdragon 732G | LineageOS 22.2 (A15) | ✅ |
| **Redmi 4X** | `santoni` | Snapdragon 435 | LineageOS 22.2 (A15) | ⚠️ |
| **Galaxy Note II** | `t0lte` | Exynos 4412 | LineageOS 21.0 (A14) | ⚠️ |

---

## 📦 Build Variants

Choose the variant that best fits your needs from the [Releases](../../releases) page:

*   **Base (Normal):** Focused on daily stability and performance.
*   **Droidspace (DS):** Integrated LXC/Droidspace support for containerization and system isolation.
*   **NetHunter (NH):** Tailored for security research. Includes USB HID Gadget support (keyboard/mouse emulation) and extensive WiFi Injection drivers for external adapters.
*   **Modem (MDM):** Optimized for 24/7 network operation. Features TCP BBR congestion control and "Fake Battery" support for bypass/no-battery setups.

---

## 🛡️ Key Features

*   **KernelSU:** Built-in kernel-based root solution. Secure and compatible with modern detection bypass.
*   **Hardware LED Status:** Visual feedback for system status (Heartbeat, Panic blink).
*   **Optimized Networking:** Enhanced TCP performance and network scheduling (MDM variant).
*   **AnyKernel3:** Seamless installation via TWRP or any custom recovery.

---

## 📥 Installation

1.  Download the correct ZIP file for your device and preferred variant from the [**Releases**](../../releases) tab.
2.  Boot into your Custom Recovery (TWRP/OrangeFox/etc).
3.  (Optional but Recommended) Backup your current `Boot` and `DTBO` partitions.
4.  Flash the downloaded ZIP file.
5.  Reboot system.

---

## ⚠️ Disclaimer

> [!CAUTION]
> **Use at your own risk.** We are not responsible for bricked devices, dead SD cards, or any hardware damage. Flashing custom kernels will void your warranty.
>
> By using this kernel, you agree that **you are solely responsible** for any damage to your device or loss of data.

---


*Developed with ❤️ by the LiCIK.*
