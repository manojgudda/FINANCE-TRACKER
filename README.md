# FinanceOS 🚀

A premium, comprehensive personal finance and analytics dashboard. Built as a flagship portfolio piece, FinanceOS moves beyond simple CRUD operations to integrate real-time APIs, AI vision processing, algorithmic debt splitting, and web scraping into a sleek, dark-mode SaaS interface.

## ✨ Core Features

* **📊 Dynamic Dashboard:** Live summary cards, visual budget progress bars, and an animated Chart.js spending breakdown.
* **🤖 AI Vision Scanner:** Upload a restaurant receipt and use Optical Character Recognition (OCR) to automatically extract the title and total amount to log the transaction.
* **📈 Live Crypto Trading Desk:** Fetches real-time cryptocurrency data via the CoinGecko REST API, allowing users to "trade" virtual assets and track live portfolio value.
* **🍕 Splitwise Algorithm:** A shared-expense engine that divides bills among friends, tracks outstanding debts, and automatically logs the user's personal share to their master ledger.
* **🛒 Product Intelligence Tracker:** Scrapes e-commerce URLs to track product prices, calculates buy recommendations based on historical highs/lows, and compares competitor pricing.
* **🏛️ Tax Hub & Smart Tools:** Instant calculators for GST and New Regime Income Tax Returns (ITR), plus a "Smart Cart" affordability engine.
* **⚙️ Automation & Ledger:** Background triggers for recurring monthly subscriptions, full transaction history, and one-click CSV exporting.

## 🛠️ Tech Stack

* **Backend:** Python, Django
* **Database:** MongoDB (via `pymongo`)
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5.3
* **Data Visualization:** Chart.js
* **AI/Machine Learning:** `pytesseract` (Tesseract OCR), `Pillow`
* **Web Scraping & APIs:** `requests`, `BeautifulSoup4`

## 🚀 Getting Started

### Prerequisites
Make sure you have Python and MongoDB installed on your system. You will also need Tesseract-OCR installed on your machine if you wish to use the AI Receipt Scanning feature.

