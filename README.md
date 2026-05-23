# 🇮🇹 Italy Schengen Visa Appointment Notifier

A Python-based automation tool that monitors Italy Schengen Visa appointment availability for Istanbul locations and sends real-time mobile notifications via the Pushbullet API whenever a slot becomes available.

## 📝 Project Description

Securing a visa appointment can be challenging due to high demand. This project automatically tracks the availability of "Tourist Visa" and "Standard Service" appointment slots at the Italian Consulate in Istanbul. The moment an active appointment date is detected, it instantly triggers a push notification to your mobile device using Pushbullet.

## 🚀 Features

* **Automated Monitoring:** Continually checks appointment dates for "Tourist Visa" and "Standard Service" categories in Istanbul.
* **Instant Alerts:** Sends immediate mobile push notifications via the Pushbullet API as soon as an opening is detected.
* **Lightweight & Efficient:** Utilizes clean HTTP requests to fetch status updates without heavy overhead.

## 🛠️ Prerequisites

* Python 3.x
* `requests` library
* `pushbullet.py` library

## 🔧 Installation & Setup

1. **Install Dependencies:**
   Ensure you have Python 3.x installed. Run the following command to install the required libraries:
   ```bash
   pip install requests pushbullet.py
