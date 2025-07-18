﻿# ais-monitoring-tool
# 🚢 AIS Monitoring Tool

A Python-based web scraping tool to monitor live maritime vessel data using the Automatic Identification System (AIS). This project extracts structured JSON data from [MarineTraffic](https://www.marinetraffic.com) and exports it to CSV for further analysis.

---

## 📌 Features

- 📡 Fetches **real-time ship data** (position, speed, heading, destination, etc.)
- 🧠 Bypasses scraping restrictions using **Selenium browser automation**
- 🔄 Converts structured **JSON to CSV**
- 💻 Portable, clean, and modular Python code
- ⏰ Ready for automation using **cron jobs**

---

## 🧪 Why Selenium?

Direct requests to the data endpoint (`.json`) result in a **403 Forbidden error** due to web protection (CORS, Cloudflare, etc.). This tool uses **Selenium to simulate a real browser session**, bypassing those restrictions and allowing JSON access.

---

## 🧰 Tech Stack

- **Python 3**
- **Selenium** for browser automation
- **ChromeDriver**
- **JSON & CSV** data handling
- **Chrome DevTools** (to inspect requests)
- (Optional) `webdriver_manager` for ease of driver setup

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ais-monitoring-tool.git
cd ais-monitoring-tool
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```


