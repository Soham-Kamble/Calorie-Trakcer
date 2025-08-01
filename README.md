# 🥗 Calorie Tracker — Django Web App

A modern, responsive web application built with **Django** that allows users to track their daily calorie and macronutrient intake. Users can add food items they've consumed, see real-time progress toward their daily goals, and view a breakdown of carbs, protein, and fats through interactive charts.

---

## 🚀 Features

- ✅ Add food items from a predefined list
- 📊 Real-time calorie goal progress bar
- 🍽️ Macronutrient breakdown via Chart.js doughnut chart
- 📅 Daily food consumption table with totals
- 🗑️ Option to remove items
- 🔐 Admin interface to manage food database
- 📱 Responsive UI with Bootstrap 5

---

## 📸 Screenshots

> Add your own screenshots or GIF demos here  
> Example:
> ![Screenshot of Calorie Tracker Dashboard](screenshots/dashboard.png)

---

## 🛠️ Built With

- [Django](https://www.djangoproject.com/)
- [Bootstrap 5](https://getbootstrap.com/)
- [Chart.js](https://www.chartjs.org/)
- SQLite (default Django DB)

---

## 🚀 Installation Guide

Follow these steps to set up and run the **Calorie Tracker** Django app locally:

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/calorie-tracker.git
cd calorie-tracker
```

---

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

> 💡 **Note:** On Windows, use `python -m venv venv` and activate with `venv\Scripts\activate`.

---

### 3️⃣ Activate the Virtual Environment

```bash
source venv/bin/activate   # For macOS/Linux
```

```bash
venv\Scripts\activate      # For Windows
```

---

### 4️⃣ Install the Dependencies

```bash
pip install -r requirements.txt
```

---

### 5️⃣ Apply Database Migrations

```bash
python manage.py migrate
```

---

### 6️⃣ (Optional) Create a Superuser

```bash
python manage.py createsuperuser
```

> 🔐 This allows you to access the Django admin panel at `/admin`.

---

### 7️⃣ Run the Development Server

```bash
python manage.py runserver
```

---

### ✅ You're Done!

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

Enjoy tracking your calories! 🥗🔥
