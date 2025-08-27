# 🛡️ PhishCan Threat Feeds

Real-time curated lists of Canadian phishing domains, automatically updated from the PhishCan VPS.

---

## 📑 Summary
- [📊 Current Stats](#-current-stats)
- [📂 Repository Structure](#-repository-structure)
- [📥 Download Feeds](#-download-feeds)
- [⚙️ API Formats](#-api-formats)

---

## 📊 Current Stats
- 🏦 **Banking**: 3830 domains (last updated: 2025-08-27 13:43:31Z)
- ⚡ **Utilities**: 962 domains (last updated: 2025-08-27 13:43:31Z)

---

## 📂 Repository Structure
```
phishcan-data/
├── data/                 # Latest raw feeds + metadata
│   ├── banking/
│   │   ├── canadian_bank_phishing_domains.txt
│   │   └── metadata.json
│   └── utilities/
│       ├── canadian_utilities_phishing_domains.txt
│       └── metadata.json
│
├── api/                  # Developer-friendly formats (JSON, JS, CSV)
│   ├── banking/
│   └── utilities/
│
├── archive/              # Historical snapshots (timestamped TXT)
│   ├── banking/
│   └── utilities/
│
└── README.md             # Auto-updated with stats + links
```

---

## 📥 Download Feeds
- 🏦 Banking:
  - [TXT](data/banking/canadian_bank_phishing_domains.txt)
  - [JSON](api/banking/canadian_bank_phishing_domains.json)
  - [JS](api/banking/canadian_bank_phishing_domains.js)
  - [CSV](api/banking/canadian_bank_phishing_domains.csv)
- ⚡ Utilities:
  - [TXT](data/utilities/canadian_utilities_phishing_domains.txt)
  - [JSON](api/utilities/canadian_utilities_phishing_domains.json)
  - [JS](api/utilities/canadian_utilities_phishing_domains.js)
  - [CSV](api/utilities/canadian_utilities_phishing_domains.csv)

---

## ⚙️ API Formats
Feeds are also consumable directly in structured formats (JSON, JS, CSV) under `/api/...`.
