# 🎟️ BookMyShow Show Alert Bot

Get notified instantly when bookings open for your selected movie, theatre, and showtime on BookMyShow.  
Perfect for high-demand shows like IMAX, recliner seats, or weekend blockbusters.

---

## ⚡ Problem

Popular shows often open without notice and get booked out in minutes.  
Users keep refreshing BookMyShow hoping to catch the slot — and still miss the seats they want.

---

## ✅ What This Bot Does

- Monitors a specific **movie link**, **theatre**, and **showtime**
- Sends Telegram alerts when:
  - Booking opens
  - *(Optional)* Your preferred seats (e.g., rows G-J) are available
- Works on:
  - Laptop or PC (Windows/Linux/Mac)
  - Android phone via **Termux**
  - Cloud (GCP, Railway, etc.)

---

## 💬 Example Notification

> 🎬 Booking Open: [Movie Name]  
> 📍 [Theatre], 🕒 [Showtime]  
> 👉 Tap to Book: [BMS link]

---

## 🛠 Tech Stack

- Python 3
- BeautifulSoup (HTML parsing)
- Telegram Bot API
- Termux (optional mobile deployment)

---

## 📦 Installation

```bash
git clone https://github.com/your-username/bms-show-alert-bot.git
cd bms-show-alert-bot
pip install -r requirements.txt


  
