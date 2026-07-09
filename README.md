# 🇭🇰 QTPhone Demo — Global Independent IP Cloud Phone

Welcome to the official **QTPhone** demo repository.

🌐 **Website:** https://www.qtphone.com/

QTPhone provides **cloud Android devices with dedicated, independent IPs** — built for
social-media marketing, automation, gaming multi-instance, and large-scale app testing.

---

## 🔧 What this repo shows

This repo demonstrates two QTPhone core capabilities:

1. **ip_check.py** — Verify your cloud device's public IP address (each QTPhone instance gets its own independent IP)
2. **device_status_checker.py** — Check real-time device status: screen, battery, network, installed apps, and IP (useful for managing a cloud device fleet)

## 🔌 Quick start

`ash
# Run IP checker (from any QTPhone cloud device)
python ip_check.py

# Run device status checker
python device_status_checker.py
`

### Sample output — ip_check.py

`
QTPhone Independent-IP Checker
------------------------------
Public IP : 203.0.113.42
Org / ISP : Example-Datacenter LLC
Country   : HK
Verdict   : ✅ Independent public IP detected
`

### Sample output — device_status_checker.py

`
QTPhone Device Status Checker
============================== Firmware  : Android 14
CPU Arch  : arm64-v8a
------------------------------
Screen    : ON (1080x2400 @ 60Hz)
Battery   : 85% | Charging: Yes
Network   : WiFi | SSID: QTPhone-Cloud
IP        : 203.0.113.42 (HK)
------------------------------
Installed apps (top 5):
  com.whatsapp      - WhatsApp
  org.telegram.messenger - Telegram
  com.twitter.android    - Twitter/X
  com.instagram.android  - Instagram
  com.snapchat.android   - Snapchat
Verdict  : ✅ All systems operational
`

## 💡 Use cases

| Use case | Why QTPhone |
|----------|-------------|
| Social media marketing | Run many accounts, each on its own IP — no cross-linkage |
| Automation & bots | Scale scripts across isolated cloud Android instances |
| Multi-instance gaming | Parallel sessions without hardware or bans |
| App testing | Test across real devices and real geolocations |
| Fleet management | Monitor status of all cloud devices from one dashboard |

## 📂 File overview

| File | Description |
|------|-------------|
| ip_check.py | Public IP verification tool |
| device_status_checker.py | Cloud device health & status checker |
| README.md | This file |

## 📞 Contact

| Channel | Address |
|---------|---------|
| 🌐 Website | [qtphone.com](https://www.qtphone.com/) |
| 💬 WhatsApp | @along915 |
| ✈️ Telegram | [@Alongyun](https://t.me/Alongyun) |
| 📧 Email | ailong9281@gmail.com |

---

*QTPhone — Global Independent IP Cloud Android Devices.*