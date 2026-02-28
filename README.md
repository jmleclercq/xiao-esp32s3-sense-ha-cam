# XIAO ESP32S3 Sense + ESPHome + Home Assistant

ESPHome camera project for integrating a Seeed Studio XIAO ESP32S3 Sense into Home Assistant.

This repository provides a clean, reproducible and extensible starting point.

---

## 🎯 Project Goals

- ✅ Working ESPHome YAML configuration
- ✅ Camera streaming & snapshot (HTTP)
- ✅ Native Home Assistant integration (API)
- ✅ OTA updates
- 🔜 Future extensions: audio, SD storage, enclosure, direct power supply

---

## 🧰 Hardware

- Seeed Studio XIAO ESP32S3 Sense (ESP32-S3 + PSRAM + camera)
- USB-C data cable
- 5V power supply (temporary solution)

---

## 🏗 Architecture

- ESPHome (firmware generation)
- Native ESPHome API → Home Assistant
- Optional HTTP camera stream (debugging)
- OTA updates once deployed

---

## 🚀 Quick Start

### 1️⃣ Configure secrets

```bash
cp esphome/secrets.yaml.example esphome/secrets.yaml
