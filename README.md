# KRACK Attack Simulation

This project demonstrates the KRACK (Key Reinstallation Attack) vulnerability in WPA2 WiFi networks. It highlights how an attacker can replay part of the 4-way handshake, forcing a victim to reinstall an already-used encryption key and enabling traffic decryption or injection.

---

## Project Highlights

- **Simulated Environment**:  
  - Hostapd-based access point or real WPA2 router  
  - Kali Linux attacker machine with USB WiFi adapter  
  - Victim device (laptop, phone, or Raspberry Pi)

- **Attack Flow**:  
  1. Set up WPA2 network  
  2. Connect victim device  
  3. Use aircrack-ng to capture the handshake  
  4. Replay handshake message 3 with KRACK PoC scripts  
  5. Analyze decrypted packets in Wireshark

- **Defensive Takeaways**:  
  - Modern patches prevent key reinstallation  
  - Updated WPA2 implementations mitigate this attack

---

## Tools & Requirements

✅ Kali Linux  
✅ aircrack-ng, hostapd, wpa_supplicant  
✅ Wireshark  
✅ USB WiFi adapter with monitor mode

---

## Educational Purpose

This project is **educational**—no unauthorized testing! It shows why WPA2 updates matter and how traffic analysis can expose vulnerabilities.

---

### Author & Usage
- **Author**: [Your Name / Handle]  
- **Run**: Follow the outlined workflow to capture, replay, and analyze the handshake vulnerability.

---
## Demo
https://drive.google.com/file/d/10T66eKLolYu2TuZAxhu_1zFxV_TwsrSH/view

**A quick dive into WPA2’s KRACK vulnerability—secure your networks!**
