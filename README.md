
# BLACK CRACKER - Wi-Fi Attack Suite for ESP32

**BLACK CRACKER** is a powerful, menu-driven Wi-Fi attack suite built for the ESP32 with OLED + Rotary Encoder support. Designed for on-the-go red teaming, wireless penetration testing, and cybersecurity demonstrations — right from your pocket.

> **DISCLAIMER:** This tool is intended for **educational** and **authorized security research** only. Use responsibly and only on networks you own or have explicit permission to test.

---

## Features

- **Rotary Encoder Navigation**  
  - Scroll & select attacks like a hacker boss.
- **OLED Display Interface**  
  - Real-time feedback and clean UI.
- **Modular Attack System**  
  - Easily toggle attacks via menu.

### Attack Modules:
- **Deauthentication Attack** – Disconnect devices from Wi-Fi networks.
- **Beacon Spam** – Flood target devices with fake SSIDs.
- **Probe Flood** – Confuse clients by mimicking probe requests.
- **Hidden SSID Reveal** – Detect hidden Wi-Fi networks.
- **SSID Cloning** – Clone legit networks to lure users.
- **Fake AP Flood** – Create multiple rogue access points.
- **Karma Attack** – Respond to probe requests with spoofed SSIDs.
- **MAC Randomization** – Obfuscate your identity.
- **Targeted Deauth** – Kick specific clients off specific networks.
- **Channel Hopper** – Cycle through channels for broader scanning/attacks.

---

## Hardware Requirements

- **ESP32 Dev Board**
- **0.96" OLED Display (SSD1306 I2C)**
- **Rotary Encoder with Push Button**
- **(Optional)**: External antenna or LiPo battery for field testing

---

## Installation

1. **Clone this repo:**
   ```bash
   git clone https://github.com/yourname/blackcracker.git
   cd blackcracker

CONNECTIONS::
    0.96 INCH OLED DISPLAY
    GND-GND
    VCC-3.3V
    SCL-D22 OR GPIO22
    SDA-D21 OR GPIO21

ROTARY ENCODER WITH PUSH BUTTON (KY-040)
     GND-GND
     + OR VCC - 3.3V
     SW- D32 OR GPIO 32
     DT - D35 OR GPIO 35
     CLK- D34 OR GPIO 34

