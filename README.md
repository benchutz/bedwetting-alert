# Bedwetting Alert System

A Raspberry Pi–powered hardware project that detects nighttime moisture events and triggers sound and light alerts. Designed to support a neurodivergent young adult with complex sensory and medical needs — with a strong emphasis on dignity, discretion, and reliability.

---

## 💡 Features

- Real-time moisture detection using a capacitive sensor
- Multi-mode LED indicators (dim glow, flash, steady)
- Audible buzzer alerts with customizable tones
- All components run at safe voltages (3.3V/5V)
- SSH-based development and remote operation
- Code written in Python with `RPi.GPIO`

---

## 🛠 Hardware Used

- Raspberry Pi Zero 2 W
- Breadboard (400-pin)
- Blue LED + 330Ω resistor
- Active buzzer module
- Capacitive moisture sensor module
- Jumper wires (F-M, M-M)
- MicroSD card + power supply

---

## 🚀 Getting Started

1. **Clone this repo** (on your Pi):

   ```bash
   git clone https://github.com/YOUR_USERNAME/bedwetting-alert.git
   cd bedwetting-alert

2. **Run hardware test scripts**:

   ```bash
   python3 led_alert_test.py
   python3 buzzer_test.py
   python3 moisture_test.py
   ```

3. **Run full system (coming soon):**

   ```bash
   python3 bedwetting_alert.py

---

## 🧐 Design Philosophy

* Start simple → build confidence through small wins
* Prioritize user dignity and comfort
* Document everything for future handoff
* Treat it like a real assistive device, not a one-off

---

## 📜 License

This project is open source and freely available for personal use.
If you adapt or build on it for your own needs, please consider contributing back any improvements.
