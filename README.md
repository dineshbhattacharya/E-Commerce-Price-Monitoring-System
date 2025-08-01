# 🛒 E-Commerce Price Monitoring System

## 🧠 Description

This project is an automated **E-Commerce Price Monitoring System** built using **Python, Flask, and PostgreSQL**. It monitors and tracks product prices across multiple e-commerce platforms in real time and provides users with alerts and historical price data via a REST API.

The system uses web scraping to track **1000+ products** across **5+ major platforms**. It alerts users when prices drop and stores all historical data in a PostgreSQL database. A Flask-based API serves client applications and enables users to retrieve pricing trends and history efficiently.

---

## 🚀 Features

- ✅ **Automated Web Scraping**  
  Monitors prices of products from multiple e-commerce websites using BeautifulSoup and/or Selenium.

- ✅ **Real-Time Price Alerts**  
  Sends alerts to users when price drops are detected or thresholds are met.

- ✅ **RESTful API with Flask**  
  Exposes endpoints for users to query product data, trends, and price histories.

- ✅ **PostgreSQL Integration**  
  Stores historical pricing data in a normalized relational schema for analytics.

- ✅ **User Tracking**  
  Supports 100+ users accessing and monitoring product histories via the API.

---

## 📁 Project Structure

```plaintext
ecommerce-price-monitor/
├── app/
│   ├── __init__.py           # Flask app factory
│   ├── routes.py             # API endpoints
│   ├── scraper.py            # Web scraping logic
│   ├── alerts.py             # Alerting system
│   └── models.py             # ORM models (SQLAlchemy)
│
├── migrations/               # Database migration scripts
├── static/                   # Static assets (if web UI is added)
├── templates/                # HTML templates (optional)
├── config.py                 # Configuration and environment variables
├── requirements.txt          # Python dependencies
├── run.py                    # Entry point to start Flask server
└── README.md                 # Project documentation
```

---

## 📈 Results
🕒 Real-time monitoring of 1000+ products across 5+ platforms

📉 Automatic price-drop alerts to subscribed users

🔌 REST API serving 100+ active users with pricing insights

---

## 📌 Future Improvements
🌐 Add a lightweight web dashboard using Flask/Jinja or React

📲 Integrate Telegram or Email notifications for alerts

📊 Include machine learning-based trend prediction (e.g., price forecasting)

---

## 🛠 Technologies Used
🐍 Python

🌐 Flask (REST API)

🗄️ PostgreSQL (Database)

🧪 BeautifulSoup / Selenium (Web scraping)

🧰 SQLAlchemy (ORM)

⚙️ Cron / APScheduler (Task scheduling)

---

## 📫 Contact

For questions or collaboration:  
**Dinesh Bhattacharya**  
📧 dineshbhattacharya2002@gmail.com
🔗 [LinkedIn / Portfolio link if applicable]

---

⚠️ Note: This project was developed for learning and demo purposes. For production use, add scraping resilience (e.g., anti-bot evasion) and caching.
