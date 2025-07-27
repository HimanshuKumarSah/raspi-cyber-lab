# 🛡️ Raspberry Pi Cybersecurity Lab

> Personal cybersecurity research & testing environment built on a Raspberry Pi 4

## 📌 Overview
A Raspberry Pi 4 configured as a portable, self-contained **Wi-Fi security testing and monitoring toolkit**.  
This project explores offensive and defensive security concepts, Wi-Fi auditing, and real-time network analysis — fully controlled within a legal, isolated lab setup.

---

## 🧰 Tools & Features

| Category                   | Tools & Purpose                                                                                             |
|---------------------------:|-------------------------------------------------------------------------------------------------------------|
| **Wi-Fi Auditing**        | ✅ `aircrack-ng` – capture and crack WPA/WPA2 handshakes<br>✅ `mdk3` – deauthentication attacks<br>✅ `wifite2` – automated capture & cracking |
| **Advanced Capture**      | ✅ `hcxdumptool` – PMKID and handshake capture<br>✅ `hcxpcapngtool` – convert captures to hashcat formats |
| **Cracking**              | ✅ `hashcat` – dictionary & hybrid attacks on captured hashes<br>✅ Custom scripts for automated handshake collection |
| **Recon & Scanning**      | ✅ `nmap` – network mapping and service detection |
| **Penetration Testing**   | ✅ `Metasploit Framework` – exploit research and testing |
| **Evil Twin & Rogue AP**  | ✅ `Bettercap` – clone networks, capture credentials, man-in-the-middle (MITM) traffic |
| **Wordlists**             | ✅ `SecLists` & `rockyou.txt` – password lists for cracking |
| **Utility**               | ✅ `macchanger` – anonymize MAC addresses<br>✅ Custom bash scripts – automate attacks and logging |

---

## 🔧 Custom Scripts & Automation
- ⚡ Automated handshake capture script: scan networks → select target → deauth → capture → save
- ⚡ Evil Twin script: list APs → clone selected → optional deauth → capture HTTPS logs
- 🧪 Manual cracking workflow with hashcat using custom patterns, hybrid and brute-force modes

---

## 🛡️ Ethical & Controlled Use
All experiments were conducted **only on networks owned by me** or explicitly authorized test networks, for educational and research purposes.

---

## 🌟 Key Takeaways / What I Learned
- Wireless security fundamentals: WPA/WPA2 handshake flow, PMKID attacks
- Capture & cracking techniques with real hardware
- MITM techniques and rogue AP setups
- Automating offensive tooling with bash
- Managing Linux security tools on ARM architecture
- Secure remote access and VPN setups (planned)

---

## 🚀 Future Steps
- Build a small dashboard to visualize capture logs & attempts
- Explore containerization (Docker) for isolation of security tools

---

## 📂 Tech Stack
- **Hardware:** Raspberry Pi 4, USB Wi-Fi adapter, 128GB microSD
- **OS:** Raspberry Pi OS (Lite)
- **Languages:** Bash
- **Tools:** aircrack-ng, hashcat, hcxtools, bettercap, metasploit, wifite2, nmap, SecLists

---

## 📄 License
For educational & personal use only.  
⚠ Unauthorized use on networks you do not own or have explicit permission to test is illegal.

---

## ✏️ Author
**Himanshu Kumar S.**  
Cybersecurity enthusiast & maker
