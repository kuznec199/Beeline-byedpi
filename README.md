# Beeline Smart Box N300 — ByeDPI Binary (Lexra Architecture)

Compiled **ByeDPI** binary file for the legendary **Beeline Smart Box N300** router (as well as other Smart Box revisions based on Realtek chipsets). 

This build is customized for the **Lexra** hardware architecture (modified MIPS, Realtek RTL8196E / RTL8197G, and similar chipsets) to operate directly on your home router.

---

## 🔍 Key Features / Optimization (SEO)
* **Compatibility**: Beeline Smart Box N300, Smart Box One (depending on the revision).
* **Build Specifications**: Compiled taking into account the limitations of older Linux kernels and the specific instruction sets of Realtek/Lexra processors.
* **Stability**: Fixed critical startup failure issues following a hard reboot of the device and process freezing/hanging during prolonged continuous operation.

---

## 🚀 Installation and Usage

1. Download the latest binary file from the **Releases** section: https://github.com/kuznec199/Beeline-byedpi/releases
2. Upload the file to your router (into the `/tmp` directory or onto a connected USB flash drive if using custom firmware like OpenWrt / Padavan / Keenetic).
3. Grant execution permissions to the file:
   ```bash
   chmod +x byedpi-lexra
   ```
4. Run ByeDPI with the required parameters (basic working example):
   ```bash
   ./byedpi-lexra --disorder 1 --split 2 --ttl 4
   ```

---

## 📝 Changelog

### Version 1.1.0
* **English**:
  - Fixed a startup issue after a hard reboot.
  - Fixed freezing during prolonged operation.

 
---

## ℹ️ Sources and Credits
This project is a custom build of the original **ByeDPI** tool.
* Original project source code: [hresrcc/ByeDPI](https://github.com/hufrea/byedpi)


