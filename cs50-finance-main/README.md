# CS50 Finance – Final Project

This is a stock trading simulator web application built with **Flask**, **Python**, **SQLite**, and **Jinja2 templates**.  
Users can register, log in, look up real-time stock prices via API, and simulate buying/selling shares with virtual cash.

## 🧾 Features

- ✅ User registration & login system (with hashed passwords)
- ✅ Real-time stock quote lookups using [IEX Cloud API](https://iexcloud.io/)
- ✅ Buy and sell stocks with live price checks
- ✅ View transaction history and current portfolio
- ✅ Input validation and flash messaging
- ✅ Uses SQLite for data persistence

## 💻 Tech Stack

- **Frontend:** HTML, CSS, Bootstrap, Jinja2
- **Backend:** Python (Flask)
- **Database:** SQLite
- **API:** IEX Cloud (for real-time stock quotes)

## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/cs50-finance.git
   cd cs50-finance

2. Set up environment:
```bash
pip install -r requirements.txt
export FLASK_APP=application.py
export API_KEY=your_iexcloud_api_key
flask run
```

3. Open browser and go to:
   ```cpp
   http://127.0.0.1:5000/

## Folder Structure
```cpp
/finance/
├── application.py
├── helpers.py
├── templates/
│   ├── layout.html
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   └── ...
├── static/
│   └── styles.css
├── finance.db
├── requirements.txt
└── README.md
```

## 🧠 Concepts Applied
```markdown
Web development (Flask routing, templates, forms)

User authentication (login sessions, password hashing)

Server-side validation and error handling

SQL queries (SELECT, INSERT, UPDATE)

RESTful APIs and JSON parsing
```
