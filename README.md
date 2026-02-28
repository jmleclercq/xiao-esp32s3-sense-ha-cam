# XIAO ESP32S3 Sense + ESPHome + Home Assistant

![ESPHome](https://img.shields.io/badge/ESPHome-Compatible-000000?logo=esphome)
![Home Assistant](https://img.shields.io/badge/Home%20Assistant-Compatible-41BDF5?logo=homeassistant&logoColor=white)
![ESP32-S3](https://img.shields.io/badge/ESP32-S3-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Maintained](https://img.shields.io/badge/Maintained-Yes-brightgreen)
![Status](https://img.shields.io/badge/Status-Active-success)

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

- Seeed Studio XIAO ESP32S3 Sense  
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
