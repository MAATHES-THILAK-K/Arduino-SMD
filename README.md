# Arduino-SMD

This project is a compact, stylish, Arduino-compatible development board based on the **ATmega328P-AU** (TQFP). It includes several integrated peripherals making it ideal for wearable or IoT projects.

---

## 📦 Components

| Component | Description |
|----------|-------------|
| **ATmega328P-AU** | 8-bit microcontroller (TQFP) |
| **AMS1117-3.3V LDO** | 5V to 3.3V regulator for APDS9960 & HC-05 |
| **TLV76750** | 12V to 5V LDO |
| **WS2812B** | RGB LED (Smart addressable) |
| **APDS-9960** | Gesture sensor (I2C) |
| **HC-05** | Bluetooth module |
| **Tactile Switch** | User input |
| **Active Buzzer** | Sound feedback |
| **USB-C (Power-only)** | 5V input only (no data lines) |
| **12V Barrel Jack** | Additional power input |
| **ICSP Header (2x3)** | For firmware flashing |
| **GPIO Headers** | Female headers for D0-D13, A0-A5 |
| **Various SMD Resistors & Capacitors** | For pull-ups, bypassing, filtering |

---

## ⚠️ Warning

> **The DRC (Design Rule Check) in KiCad was not fully resolved during initial layout. There may be trace width, clearance, or connectivity issues. Please verify the layout manually or run a complete DRC pass before fabrication.**

---

## 📁 Folder Info

- **Gerber/** → Ready-to-export Gerber files for fabrication  
- **KiCad_Project/** → All source files for the schematic & layout  
- **images/** → (Optional) Screenshots, 3D renders of the board  
- **LICENSE** → MIT License for reuse  
- **.gitignore** → Standard for KiCad projects  

---

## 🛠️ To-Do
- [ ] Fix all DRC errors
- [ ] Add 3D renders
- [ ] Test hardware once fabricated
