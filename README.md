# 🛡️ PhishCan Threat Feeds

This repository provides fresh phishing domain feeds for Canadian **banks 🏦** and **utilities ⚡**.

## 📊 Current Stats
- 🏦 Banking domains: 3830  
  _(last updated: 20250827T140552Z UTC)_
- ⚡ Utilities domains: 962  
  _(last updated: 20250827T140552Z UTC)_

## 📡 Feeds by Sector

### 🏦 Banking
- TXT → [data/banking/canadian_bank_phishing_domains.txt](data/banking/canadian_bank_phishing_domains.txt)  
- JSON → [api/banking/canadian_bank_phishing_domains.json](api/banking/canadian_bank_phishing_domains.json)  
- CSV → [api/banking/canadian_bank_phishing_domains.csv](api/banking/canadian_bank_phishing_domains.csv)  
- JS → [api/banking/canadian_bank_phishing_domains.js](api/banking/canadian_bank_phishing_domains.js)  

### ⚡ Utilities
- TXT → [data/utilities/canadian_utilities_phishing_domains.txt](data/utilities/canadian_utilities_phishing_domains.txt)  
- JSON → [api/utilities/canadian_utilities_phishing_domains.json](api/utilities/canadian_utilities_phishing_domains.json)  
- CSV → [api/utilities/canadian_utilities_phishing_domains.csv](api/utilities/canadian_utilities_phishing_domains.csv)  
- JS → [api/utilities/canadian_utilities_phishing_domains.js](api/utilities/canadian_utilities_phishing_domains.js)  

## 📂 Repository Structure
- `data/` → Core TXT feeds (one per sector).
- `api/` → Converted feeds in **JSON, JS, CSV** formats for easy integration.
- `archive/` → Historical snapshots of TXT feeds (latest 5 kept).
- `README.md` → Auto-updated on every sync with live stats.

## ♻️ Archive Logic
- Every sync creates a snapshot in `archive/{sector}/`.
- Snapshots are timestamped (UTC, ISO8601).
- Only the **latest 5 snapshots** are kept per sector → older ones are automatically deleted.

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
