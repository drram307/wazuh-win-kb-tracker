
# 🔍 Wazuh Windows KB Tracker

This project extends Wazuh's visibility into Windows hotfixes (KB updates) that are not always tied to software version upgrades.

## 💡 Why?
Most scanners miss standalone KB patches — a major gap in patch visibility.

## 📁 What's Inside?
- PowerShell scripts to extract KBs
- OSQuery pack for granular monitoring
- Wazuh decoder + rule to ingest and alert
- Dashboard samples for visualization
- Bonus: Alert on missing hotfixes via diff check

## 🚀 Quick Start
1. Schedule `collect-hotfixes.ps1` on Windows assets
2. Enable custom Wazuh decoder/rule
3. Visualize in Kibana or send alerts

Want to contribute? Fork it. Add dashboard ideas or enrich the rules!
