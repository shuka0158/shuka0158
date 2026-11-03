# Hi, I'm Shuka! 👋

🔍 **OSINT Researcher & Developer**  
🇬🇪 Based in Georgia | Building intelligence tools  
💻 Python • JavaScript • Security Research

---

## 🚀 Featured Project: Keftemulator

### **Keftemulator — Unified OSINT Platform**

A powerful **61-module OSINT framework** that combines native intelligence modules with the best open-source tools. Perfect for security researchers, penetration testers, and investigators.

**🔗 Repository:** https://github.com/shuka0158/Keftemulator

### Key Features

✨ **61 Intelligence Modules**
- 10 Georgian-specific tools (NAPR, cadastre, tax, courts, business registry)
- 9 Security & threat intelligence modules
- 8 Email & breach databases
- 10 Company & financial intelligence
- 6 Social media & people search
- 5+ Network reconnaissance tools

🎯 **One-Click Setup**
```bash
git clone https://github.com/shuka0158/Keftemulator.git
cd Keftemulator
bash setup.sh    # Interactive API key setup
bash run.sh      # Start at http://127.0.0.1:5050
```

🌍 **What It Does**
- **Universal OSINT**: Search username, email, domain, IP, phone, name, company, plate, VIN, image
- **Recursive Pivoting**: Automatically discover connected entities (SpiderFoot-style)
- **Interactive Visualization**: Link-analysis graph (Maltego-style) + map view
- **Case Management**: Group and merge multiple scans
- **Scheduled Monitors**: Track targets with change alerts
- **Georgian Intelligence**: NAPR registry, property records, tax lookup, court filings

📊 **61 Data Sources**
- Sherlock (400+ sites) • Maigret (3000+ sites)
- GitHub • Telegram • Wikidata • crt.sh
- Shodan • VirusTotal • AbuseIPDB
- Wayback Machine • URLScan • IntelX
- Georgian: NAPR • Cadastre • Court System

🔐 **Privacy First**
- ✅ Run locally (data stays on your machine)
- ✅ No cloud upload
- ✅ SQLite database with encryption
- ✅ Free API integrations

📱 **Mobile-Responsive Dark UI**
- Works on desktop, tablet, phone
- Beautiful graph visualization
- Full-text search
- Dark theme

### Quick Start

```bash
# 1. Clone
git clone https://github.com/shuka0158/Keftemulator.git
cd Keftemulator

# 2. Setup (interactive)
bash setup.sh

# 3. Run
bash run.sh

# 4. Open browser
http://127.0.0.1:5050
```

### Example Searches

- **Username**: `torvalds` → Finds GitHub profile, commits, emails, related accounts
- **Email**: `user@example.com` → Breaches, social media, company info
- **Domain**: `example.com` → DNS, IP, SSL certs, Wayback snapshots, related domains
- **Company**: `SwissCapital` → NAPR registry, directors, court records, financial data
- **Phone**: `+995 555 123456` → Georgian lookups, carrier, related searches
- **Plate**: `AB-123-CD` → Vehicle photos, Georgian registries

### Documentation

📖 **[INSTALL.md](https://github.com/shuka0158/Keftemulator/blob/master/INSTALL.md)** - Detailed setup & API key guide  
📚 **In-app Guide** - Click **?** button for full user guide  
💡 **GitHub Wiki** - (Coming soon)

---

## 🛠️ Tech Stack

**Backend:**
- Python 3.12
- Flask + Waitress
- SQLite (WAL mode)
- ThreadPoolExecutor (parallel scanning)

**Frontend:**
- Vanilla JavaScript (SPA)
- Cytoscape.js (graph visualization)
- Leaflet.js (map)
- Dark theme CSS

**Infrastructure:**
- Tailscale Funnel (public hosting)
- Systemd user services (auto-boot)
- Docker-ready (planned)

---

## 📊 Project Stats

- **61 modules** across 40+ intelligence sources
- **1000+ files** in codebase
- **Tested on:** Linux, WSL, Mac
- **License:** Open Source (OSINT research)

---

## 🔗 Connect

- **GitHub**: [@shuka0158](https://github.com/shuka0158)
- **Keftemulator Repo**: [github.com/shuka0158/Keftemulator](https://github.com/shuka0158/Keftemulator)

---

## ⚖️ Legal & Ethics

Keftemulator is designed for **authorized OSINT research** only:
- ✅ Security testing & penetration testing
- ✅ Intelligence research & investigation
- ✅ Educational purposes
- ❌ Unauthorized surveillance
- ❌ Data scraping without permission
- ❌ Illegal access

**Use responsibly and comply with local laws.**

---

**Built with ❤️ for open-source OSINT**
