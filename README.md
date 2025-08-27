# 🛡️ PhishCan Threat Feeds

This repository provides fresh phishing domain feeds for Canadian **banks** 🏦 and **utilities** ⚡.  

## 📊 Current Stats
- 🏦 Banking domains: **3830**
- ⚡ Utilities domains: **962**

## 📂 Repository Structure
- `data/` → Core TXT feeds (one per sector).
- `api/` → Converted feeds in **JSON, JS, CSV** formats.
- `archive/` → Historical snapshots of TXT feeds.

## ♻️ Archive Logic
- Every sync creates a snapshot in `archive/{sector}/`.
- Snapshots are timestamped (UTC, ISO8601).
- **Only the latest 5 snapshots are kept** per sector → older ones are automatically deleted.

