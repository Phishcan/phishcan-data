# 🛡️ PhishCan Threat Feeds

This repository provides fresh phishing domain feeds for Canadian **banks 🏦** and **utilities ⚡**.

## 📊 Current Stats
- 🏦 Banking domains: **42**
- ⚡ Utilities domains: **962**

## 📂 Repository Structure
- `data/` → Core TXT feeds (one per sector).
- `api/` → Converted feeds in **JSON**, **JS**, **CSV** formats.
- `archive/` → Historical snapshots of TXT feeds.

## ♻️ Archive Logic
- Every sync creates a snapshot in `archive/{sector}/`.
- Snapshots are timestamped (UTC, ISO8601).
- Only the latest **5 snapshots** are kept per sector → older ones are automatically deleted.

## 📥 Usage
You can consume feeds in multiple formats:
- Raw TXT from `data/`
- JSON, JS, or CSV from `api/`

Example:
```bash
curl -s https://raw.githubusercontent.com/Phishcan/phishcan-data/main/data/banking/canadian_banking_phishing_domains.txt
```

## 🔄 Update Frequency
Feeds are updated automatically from live phishing sources every few hours.
Snapshots are archived with timestamps (UTC).

## 📑 Feeds by Sector

### 🏦 Banking
- [TXT](https://raw.githubusercontent.com/Phishcan/phishcan-data/main/data/banking/canadian_banking_phishing_domains.txt)
- [JSON](https://raw.githubusercontent.com/Phishcan/phishcan-data/main/api/banking/canadian_banking_phishing_domains.json)
- [CSV](https://raw.githubusercontent.com/Phishcan/phishcan-data/main/api/banking/canadian_banking_phishing_domains.csv)
- [JS](https://raw.githubusercontent.com/Phishcan/phishcan-data/main/api/banking/canadian_banking_phishing_domains.js)

### ⚡ Utilities
- [TXT](https://raw.githubusercontent.com/Phishcan/phishcan-data/main/data/utilities/canadian_utilities_phishing_domains.txt)
- [JSON](https://raw.githubusercontent.com/Phishcan/phishcan-data/main/api/utilities/canadian_utilities_phishing_domains.json)
- [CSV](https://raw.githubusercontent.com/Phishcan/phishcan-data/main/api/utilities/canadian_utilities_phishing_domains.csv)
- [JS](https://raw.githubusercontent.com/Phishcan/phishcan-data/main/api/utilities/canadian_utilities_phishing_domains.js)

## ⚖️ License
This project is released under the MIT License.
