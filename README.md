> [!NOTE]
> **Status: Collection ended.** The honeypot ran for 30 days in 2025, and data collection stopped on June 20, 2025. The dashboard is a static snapshot of the final results.

# 🛡️ Cowrie Honeypot Security Dashboard

A security intelligence dashboard analyzing SSH/Telnet attacks captured by a cloud-deployed Cowrie honeypot. Provides threat analysis, malware detection, and attack pattern visualization for cybersecurity research.

**🔗 [View Dashboard](https://cjturesko.github.io/honeypot_lab/)**

---

## 🔍 Features

- **Attack Analysis**: Command frequency, login patterns, and session tracking
- **Threat Intelligence**: Multiple API integrations (VirusTotal, AbuseIPDB, IPQualityScore, IPInfo) for comprehensive IP reputation and malware analysis
- **Geographic Intelligence**: Attack source mapping and infrastructure classification
- **Threat Metrics**: Known attacker identification and IP reputation analysis
- **Data Visualizations**: Charts showing attack trends, top countries, and command patterns

## 🛠️ Technical Stack

- **Honeypot**: Cowrie SSH/Telnet honeypot on cloud infrastructure
- **Processing**: Python scripts for log analysis and data extraction
- **Visualization**: Seaborn/Matplotlib for chart generation
- **Frontend**: Bootstrap 5 responsive interface
- **APIs**: VirusTotal, AbuseIPDB, IPQualityScore, and IPInfo for comprehensive threat intelligence
- **Deployment**: Automated updates to GitHub Pages

## 📊 Dashboard Sections

- **Overview**: Attack metrics and infrastructure breakdown
- **File Analysis**: Downloaded files with VirusTotal detection results
- **Recent Attacks**: Feed of attack sessions with geographic data
- **Command Analysis**: Most executed commands and attack techniques
- **Visualizations**: Charts for login analysis, geographic distribution, and trends

## ⚙️ Automation

Updated about every 2 hours during collection via automated Python processing

---

**Security Notice**: Contains real attack data during the 2025 honeypot deployment. All artifacts represent actual threats.
