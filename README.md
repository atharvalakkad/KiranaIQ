# KiranaIQ

### Smart Stock Management for Neighbourhood Stores

KiranaIQ is a mobile-first platform that helps small kirana, general and medical stores track their stock, predict what to reorder, and avoid losses from stock-outs and expiry. The goal is simple: **never run out, never overstock, never waste.**

---

## Why KiranaIQ?

Millions of small stores in India still run on memory and paper notebooks. Shopkeepers face:

- Running out of fast-selling items and losing sales
- Overstocking slow-moving goods and blocking cash
- Losing money on expired products
- Forgetting which customer owes how much (udhaar)
- Having no data to decide how much to order from the wholesaler

---

## Problem Statement

Small retailers have no affordable, simple tool to understand their own sales. Existing inventory software is built for large stores: it is complex, expensive and not designed for shopkeepers who prefer WhatsApp and local languages. As a result, ordering decisions are made on guesswork.

---

## Our Solution

KiranaIQ lets a shopkeeper record daily sales with a quick tap, voice note or a photo of the bill. The system learns the store's sales pattern and then:

- Predicts which items will run out and when
- Suggests how much to reorder
- Warns about products nearing expiry
- Tracks customer credit and sends friendly payment reminders
- Sends a weekly sales summary on WhatsApp

---

## Key Features

| Feature | Description |
|---|---|
| Quick Sales Entry | Tap, voice or bill-photo based entry in under 10 seconds |
| Demand Forecasting | Predicts weekly demand per product using past sales, season and festivals |
| Smart Reorder List | A ready list to send to the wholesaler on WhatsApp |
| Expiry Alerts | Notifications before products expire |
| Udhaar Tracker | Records customer credit, payments and reminders |
| Weekly Report | Simple profit and best-seller summary |
| Local Language | English, Hindi and Marathi interface |
| Offline Mode | Works without internet and syncs later |

---

## Target Users

- Kirana and general stores
- Medical and stationery stores
- Small supermarkets
- Small wholesalers and distributors (future)

---

## Business Model

- **Free plan:** basic stock tracking for up to 50 products
- **Pro plan (Rs. 199/month):** forecasting, expiry alerts, credit tracking, WhatsApp reorder list
- **Future revenue:** wholesaler-sponsored product suggestions

---

## Tech Stack

- **Mobile app:** Flutter
- **Backend:** Python, FastAPI
- **Database:** PostgreSQL
- **Machine learning:** scikit-learn, XGBoost, time-series forecasting
- **Voice and OCR:** speech-to-text and OCR APIs for bill reading
- **Notifications:** WhatsApp Business API
- **Hosting:** Cloud (AWS / Google Cloud)

---

## System Architecture

1. **Mobile app:** sales entry, dashboard, alerts
2. **Backend API:** user accounts, products, sales, credit records
3. **ML engine:** demand forecasting, reorder suggestions, expiry risk
4. **Notification service:** WhatsApp and push reminders
5. **Database:** users, products, sales, suppliers, customer credit

---

## Future Scope

- Direct ordering from partnered wholesalers
- Price comparison across suppliers
- Festival and weather-based demand prediction
- Digital payments (UPI) integration
- Small-business loans based on sales history
- Multi-store support

---

## Project Status

Idea stage. Created as part of the Entrepreneurship Development and Startup Lab (EDSL) at Dr. D. Y. Patil Institute of Technology, Pimpri, Pune.

---

## Author

**Atharva Vinod Lakkad**
Department of Artificial Intelligence and Data Science
Dr. D. Y. Patil Institute of Technology, Pimpri, Pune
