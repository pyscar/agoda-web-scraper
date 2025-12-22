# Agoda Hotel Web Scraper

A Python web scraper built with **Playwright** to extract hotel data from Agoda search result pages.

The scraper collects:
- Hotel name
- Location
- Price
- Rating score
- Rating text
- Review count
- Valid hotel page link


---

## 🚀 Features

- Handles dynamic scrolling
- Removes duplicate hotels
- Skips invalid / empty rows
- Outputs clean CSV data
- Uses Playwright for reliability

---

## 🛠️ Tech Stack

- Python 3.9+
- Playwright (Chromium)
- CSV

---

## 📦 Installation

### 1️⃣ Clone the repository
```
git clone https://github.com/pyscar/agoda-web-scraper.git
cd agoda-web-scraper
```
### 2️⃣ Create and activate a virtual environment (recommended)
```bash
```
**Windows**
```
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
---

### 4️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

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

You will be prompted to enter:

* Agoda search URL
* Output CSV file name (without `.csv`)

---

## 📄 Output

The scraper generates a CSV file containing:

* Hotel
* Location
* Price
* Rating Score
* Rating Text
* Review Count
* Link

---

## ⚠️ Disclaimer

This project is intended for **educational purposes only**.
Please respect Agoda’s terms of service and website policies when scraping.

---

## 📜 License

MIT License

```




