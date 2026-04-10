# 💰 Personal Expense Tracker

A Python GUI-based application to track income and expenses with real-time balance updates, file storage, and alert notifications.

---

## 🚀 Features

* ➕ Add income and expenses
* 📂 Categorize transactions
* 📊 View transaction history
* 💰 Automatic balance calculation
* ⚠️ Low balance alerts
* 📧 Email notifications
* 📱 SMS notifications (via Twilio)
* 💾 Data stored in JSON file

---

## 🛠️ Technologies Used

* Python
* Tkinter (GUI)
* JSON (Data Storage)
* SMTP (Email Alerts)
* Twilio API (SMS Alerts)

---

## 📂 Project Structure

```
personal-expense-tracker/
│── expense_tracker.py
│── expenses_data.json
│── .env (not uploaded)
│── README.md
│── .gitignore
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Akashhs2006/personal-expense-tracker.git
```

### 2. Navigate to project folder

```bash
cd personal-expense-tracker
```

### 3. Install dependencies

```bash
pip install python-dotenv twilio
```

### 4. Run the application

```bash
python expense_tracker.py
```

---

## ⚙️ Environment Variables (.env)

Create a `.env` file and add:

```
GMAIL_USER=your_email
GMAIL_PASS=your_password
RECEIVER_EMAIL=receiver_email

TWILIO_SID=your_sid
TWILIO_TOKEN=your_token
TWILIO_FROM=your_number
USER_PHONE=your_phone

DATA_FILE=expenses_data.json
LOW_BALANCE_THRESHOLD=100.0
```

---

## ⚠️ Important Notes

* Do NOT upload `.env` file to GitHub
* Keep your credentials secure
* Use GitHub `.gitignore` properly

---

## 📌 Future Improvements

* Add charts/graphs 📊
* Export reports (PDF/Excel)
* Add user authentication
* Web version (Flask/Django)

---

## 👨‍💻 Author

**Akash H S**
GitHub: https://github.com/Akashhs2006

## 👥 Team Members

* **Gururaj M H** (Developed core application logic and GUI)
  GitHub: https://github.com/Gururaj2005

* **Akash H S** (Implemented notification system (Email & SMS))
  GitHub: https://github.com/Akashhs2006

* **Kiran K G** (Handled data storage and testing)
  GitHub: https://github.com/Kiran1-hub

---
