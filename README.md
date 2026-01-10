# 🏨 Agoda Hotel Web Scraper

[![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python\&logoColor=white)](https://www.python.org/)
[![Playwright](https://img.shields.io/badge/Playwright-Automation-purple?logo=playwright\&logoColor=white)](https://playwright.dev/)
[![VS Code](https://img.shields.io/badge/VS%20Code-Editor-blue?logo=visual-studio-code\&logoColor=white)](https://code.visualstudio.com/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github\&logoColor=white)](https://github.com/pyscar/agoda-web-scraper)
[![Education](https://img.shields.io/badge/Educational-Purpose-orange)](https://github.com/pyscar/agoda-web-scraper)

A **Python web scraper** built with **Playwright** to extract hotel data from Agoda search result pages.
This project demonstrates a robust workflow to collect, clean, and save hotel information in CSV format.

---

## 📋 Features

* Handles dynamic scrolling and lazy-loaded content
* Removes duplicate hotels automatically
* Skips invalid or empty rows
* Generates clean CSV output
* Built on **Playwright** for reliable browser automation

---

## 🛠️ Tech Stack

* **Python 3.9+**
* **Playwright (Chromium)**
* **CSV** for data storage

---

## ⚡ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/pyscar/agoda-web-scraper.git
cd agoda-web-scraper
```

### 2️⃣ Create and activate a virtual environment (recommended)

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**Mac / Linux**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3️⃣ Upgrade pip (optional but recommended)

```bash
python -m pip install --upgrade pip
```

### 4️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 5️⃣ Install Playwright browsers

```bash
playwright install
```

---

## ▶️ Usage

Run the scraper:

```bash
python scraper.py
```

You will be prompted to provide:

* Agoda search URL
* Output CSV file name (without `.csv`)

The scraper will fetch and save hotel data automatically.

---

## 📄 Output

The generated CSV file includes:

* Hotel name
* Location
* Price
* Rating score
* Rating text
* Review count
* Hotel page link

---

## ⚠️ Disclaimer

This project is intended **for educational purposes only**.
Please respect Agoda’s **terms of service** and website policies when scraping.

## 👤 Author

**Oscar Kiamba**
Computer Science (AI & ML) | Data science & Ml Enthusiast

📫 Connect with me on GitHub & LinkedIn
👉 https://github.com/pyscar
👉 https://www.linkedin.com/in/oscar-kiamba/

## Complete video link for the project
* video link -> https://www.youtube.com/watch?v=ZOHx5c_UyIk


