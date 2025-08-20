# Hello-Aurdino

[![Arduino](https://img.shields.io/badge/Arduino-ready-informational)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Build](https://img.shields.io/github/actions/workflow/status/USER/hello-aurdino/ci.yml?label=CI)](#)

A minimal, well-structured Arduino starter that shows clean code style, simple serial I/O, and LED blinking. Great for beginners and quick demos.

---

## ✨ Features
- Clean `src/` with a tiny library (`hello_aurdino.*`)
- Two examples (`BlinkSerial`, `SensorRead`)
- GitHub templates for issues & PRs
- Optional PlatformIO support

---

## 🛠️ Quickstart
```bash
# 1) Clone
git clone https://github.com/USER/hello-aurdino.git
cd hello-aurdino

# 2) (Option A) Arduino IDE
#   - Open examples/BlinkSerial/BlinkSerial.ino
#   - Select your board & port, then Upload

# 2) (Option B) PlatformIO (recommended)
#   - Install VS Code + PlatformIO extension
#   - pio run -t upload
