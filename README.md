# 🟣 WebRecon

<p align="center">

```
██╗    ██╗███████╗██████╗ ██████╗ ███████╗ ██████╗ ██████╗ ███╗   ██╗
██║    ██║██╔════╝██╔══██╗██╔══██╗██╔════╝██╔════╝██╔═══██╗████╗  ██║
██║ █╗ ██║█████╗  ██████╔╝██████╔╝█████╗  ██║     ██║   ██║██╔██╗ ██║
██║███╗██║██╔══╝  ██╔══██╗██╔══██╗██╔══╝  ██║     ██║   ██║██║╚██╗██║
╚███╔███╔╝███████╗██████╔╝██║  ██║███████╗╚██████╗╚██████╔╝██║ ╚████║
 ╚══╝╚══╝ ╚══════╝╚═════╝ ╚═╝  ╚═╝╚══════╝ ╚═════╝ ╚═════╝ ╚═╝  ╚═══╝
```

</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20by-AKAZA%20SENZO-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-3.7%2B-blue?style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Linux%20%7C%20Ubuntu-black?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/API-Not%20Required-blueviolet?style=for-the-badge"/>
</p>

**WebRecon** is a powerful Python-based web reconnaissance tool with a clean magenta terminal UI. Subdomain scanning, archive hunting, DNS recon, exposed file detection, CVE checking, port scanning and more — all in one tool!

> ⚠️ **Educational Purposes Only** — This tool is built for authorized security assessments only. Only use on systems you own or have explicit permission to test. The author is not responsible for any misuse.

---

## ✨ Features

- 🔍 **Subdomain Scanner** — Wordlist based + DNS bruteforce + crt.sh passive recon
- 🗃️ **Archive Hunter** — Wayback Machine snapshots, domain timeline, deleted pages finder
- 🌐 **DNS Recon** — Full DNS records (A/MX/NS/TXT/SOA/CAA), zone transfer check, reverse lookup
- 📂 **Exposed Files** — Detects sensitive files (.env, .git, config, backup, admin panels)
- 🛡️ **CVE Checker** — Detects outdated technologies and known CVEs
- 🔌 **Port Scanner** — Top 100 ports + custom range + service banner grabbing
- 📋 **WHOIS Lookup** — Full domain & IP ownership information
- 🔗 **HTTP Method Tester** — Checks dangerous methods + CORS misconfig + Security headers
- 🟣 **Magenta Terminal UI** — Clean doom font banner
- ❌ **No API Required** — Works completely free

---

## ⚙️ Installation

### 📱 Termux
```bash
pkg update && pkg upgrade
pkg install python git
git clone https://github.com/akazatec/webrecon
cd webrecon
bash setup.sh
```

### 🐧 Linux / Ubuntu / Kali
```bash
sudo apt update && sudo apt upgrade
sudo apt install python3 python3-pip git
git clone https://github.com/akazatec/webrecon
cd webrecon
bash setup.sh
```

---

## 🚀 Usage

```bash
python3 webrecon.py
```

### 📌 Menu:
```
[1] Subdomain Scanner
[2] Archive Hunter
[3] DNS Recon
[4] Exposed Files
[5] CVE Checker
[6] Port Scanner
[7] WHOIS Lookup
[8] HTTP Method Tester
[0] Exit
```

---

## 🗂️ File Structure

| File | Description |
| :--- | :--- |
| `webrecon.py` | Main Python script. |
| `setup.sh` | Auto installer. |
| `requirements.txt` | Dependencies. |
| `CHANGELOG.md` | Version history. |
| `README.md` | Documentation. |
| `LICENSE` | MIT License. |

---

## 🤝 Contributing

Fork → Changes → Pull Request

## ⚖️ License

**MIT License** — see [LICENSE](LICENSE)

## 👤 Author

**AKAZA SENZO**
- GitHub: [@akazatec](https://github.com/akazatec)

---

<p align="center">
  <i>"Recon Deep. Find Everything."</i>
</p>
