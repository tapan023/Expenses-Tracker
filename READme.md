

# 💰 Expense Tracker (Django + React)

A full-stack expense tracking application built with **Django REST Framework** and **React**, designed to help users manage their personal finances efficiently.

This project demonstrates **full-stack skills, API integration, and modern UI design** with TailwindCSS.

---

## 🌟 Features

* **Add Expenses**: Add expense with category, amount, and date.
* **Delete Expenses**: Remove unwanted expenses easily.
* **Dashboard**: Visualize spending with **charts** and **cards**.
* **Category Emojis**: Fun emoji icons for each category.
* **Centered Responsive UI**: Modern and clean interface using **TailwindCSS**.
* **Search & Filters**: Filter by category or date range (optional feature).
* **Budget Alerts**: Show warning when budget exceeded (optional feature).
* **Export CSV**: Download your expenses for personal records (optional).
* **Dark Mode**: Toggle between light & dark theme (optional).

---

## 🛠 Tech Stack

* **Frontend**: React, Axios, TailwindCSS, Recharts.js/Chart.js
* **Backend**: Django, Django REST Framework, Django CORS Headers
* **Database**: SQLite (default, can be changed to PostgreSQL)
* **Deployment**: Can be deployed via Render / Vercel / Netlify

---

## ⚡ Screenshots

![Dashboard Screenshot](<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/005cd1b7-223c-4145-9152-33fab371d433" />
)
![Add Expense Screenshot](<img width="1917" height="968" alt="image" src="https://github.com/user-attachments/assets/60096ae3-8568-4aad-b48b-e9a55ee15259" />
)

*(Add your actual screenshots in the repo and update paths above)*

---

## 🚀 Installation

### Backend

```bash
# Navigate to backend folder
cd backend

# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows (CMD)
venv\Scripts\activate.bat
# Windows (PowerShell)
.\venv\Scripts\Activate

# Install dependencies
pip install django djangorestframework django-cors-headers

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Start server
python manage.py runserver
```

### Frontend

```bash
# Navigate to frontend folder
cd frontend

# Install dependencies
npm install

# Start React server
npm start
```

* Backend runs on `http://127.0.0.1:8000/`
* Frontend runs on `http://localhost:3000/`

---

## 🧩 API Endpoints

| Endpoint              | Method | Description       |
| --------------------- | ------ | ----------------- |
| `/api/expenses/`      | GET    | Get all expenses  |
| `/api/expenses/`      | POST   | Add a new expense |
| `/api/expenses/<id>/` | DELETE | Delete an expense |
| `/api/expenses/<id>/` | PUT    | Update an expense |

---

## 🔧 Future Improvements

* User authentication (login/signup)
* Dark mode toggle
* Budgeting alerts per category
* Export expenses to CSV/Excel
* Interactive charts with monthly/weekly summaries

---

## 📂 Folder Structure

```
expense-tracker/
│
├── backend/             # Django backend
│   ├── manage.py
│   └── ...
│
├── frontend/            # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── api.js
│   │   └── App.js
│   └── ...
│
└── README.md
```

---

## 💡 Author

**Tapan Chauhan** – Full-Stack Developer 
