# STDCRIUS-FT232RL-Basic-6-pin-Breakout-Board
A simple breakout board for the FTDI FT232RL USB-to-Serial UART interface chip. Ideal for interfacing with Arduino Pro, ESP32, ESP8266, or other microcontrollers that require a USB-to-Serial converter.

---

## 📦 Features

- ✅ FTDI FT232RL chipset
- ✅ 6-pin standard header (DTR, RX, TX, VCC, CTS, GND)
- ✅ USB Type-B Mini connector (some variants may use Micro USB)
- ✅ 3.3V / 5V selectable operation
- ✅ TX and RX LEDs for data indication

---

## 📁 Pinout Description

| Pin | Description               |
|-----|---------------------------|
| DTR | Data Terminal Ready       |
| RX  | Receive Data              |
| TX  | Transmit Data             |
| VCC | Power Output (3.3V/5V)    |
| CTS | Clear To Send             |
| GND | Ground                    |

> Note: Default jumper may be set to 5V. Check before use.

---

## 🔌 Typical Connection with Arduino Pro Mini

| FT232RL Pin | Arduino Pro Mini |
|-------------|------------------|
| DTR         | DTR              |
| RX          | TX               |
| TX          | RX               |
| VCC         | VCC              |
| GND         | GND              |

---

## ⚙️ Driver Installation

Most modern operating systems (Windows 10/11, macOS, Linux) automatically detect and install drivers. If needed:

- Windows: [FTDI Driver Download](https://ftdichip.com/drivers/)
- macOS: FTDI drivers are usually pre-installed.
- Linux: Use `dmesg | grep tty` to identify the port.

---

## 💡 Applications

- Uploading code to Arduino Pro Mini/Nano (no USB)
- Serial debugging
- Communicating with ESP8266/ESP32
- Custom embedded projects needing USB serial access

---

## ⚠️ Notes

- **Do not connect both 5V and 3.3V devices simultaneously.**
- Use proper jumper setting for voltage selection.
- Ensure TX/RX are cross-connected with the target device.

---

## 🛠️ Resources

- [FT232RL Datasheet](https://www.ftdichip.com/Support/Documents/DataSheets/ICs/DS_FT232R.pdf)
- [FTDI Official Website](https://ftdichip.com/)

---

## 📷 Image

![STDCRIUS FT232RL 6-pin Board](https://example.com/ft232rl-board-image.jpg) <!-- Replace with actual image URL -->

---

## 📝 License

This repository/documentation is released under the MIT License. You are free to use, modify, and distribute.

