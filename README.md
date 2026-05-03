# 🚀 Creality CR-5 Pro Klipper Upgrade

This project documents the complete firmware and hardware overhaul of a Creality CR-5 Pro industrial 3D printer, upgrading it to **Klipper Firmware** for enhanced speed, precision, and remote management.

## 🛠 Hardware Configuration
- **Controller:** BTT SKR Pico (STM32G0B1xx)
- **Drivers:** TMC2209 with StealthChop (Run Current: 0.580A)[cite: 1]
- **Leveling:** BLTouch Auto-bed leveling[cite: 1]
- **Host:** Raspberry Pi / Mainsail OS

## ⚙️ Key Features in Configuration
- **Precision Motion:** Optimized `rotation_distance` for X/Y (40mm) and Z (4mm) axes.[cite: 1]
- **Thermal Control:** PID-tuned hotend (300°C max) and heated bed.[cite: 1]
- **Smart Macros:** Automated `PRINT_START`, `PRINT_END`, and `LOAD_FILAMENT` routines for seamless workflow.[cite: 1]
- **Bed Mesh:** 5x5 bicubic mesh calibration for perfect first layers.[cite: 1]

## 👨‍💻 Engineering Profile
**Direnç Ferzan**
Specialized in system integration, embedded firmware, and industrial automation.
