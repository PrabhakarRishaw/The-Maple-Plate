
# 🍽️ The Maple Plate – Premium Culinary Catalog & Recipe Directory

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Python%203.11%2B%20%7C%20Django-113224?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/Frontend-Bootstrap%205%20%7C%20CSS3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/Architecture-MVT%20Pattern-007ACC?style=for-the-badge&logo=python&logoColor=white" alt="Architecture" />
</p>

---

## 🎯 Project Overview

**The Maple Plate** is a professionally structured, responsive web application engineered to showcase authentic Canadian culinary delights (such as *Poutine, BeaverTails, and Montreal Smoked Meat*). 

Built on top of the robust **Django MVT (Model-View-Template)** framework, this project serves as an ideal baseline for developers looking to understand structured context data mapping, component inheritance, and modern UI grid interfaces.

### 🌟 Key Highlights:
* **Decoupled Mock-Data Engineering:** Implements clean backend-to-frontend dictionary passing without early database dependency overhead.
* **Component-Driven UI:** Leverages semantic HTML5 alongside Bootstrap 5 for fluid responsiveness across all screens (Mobile, Tablet, and Desktop).
* **DRY Architecture:** Eliminates code redundancy by inheriting structural shells from centralized layouts.

---

## 💎 Technical Deep-Dive & Architecture

This application strictly adheres to the core principles of web engineering. Below is a deep dive into how the backend logic maps directly to the user's viewport:

### 1. Data Structuring & Context Injection (`views.py`)
The backend controller uses a native Python dictionary structure within a list to mock real-world database queries. Each object encapsulates strict property-value pairs (`strMeal`, `strMealThumb`, `idMeal`). 
Using Django's short-circuit execution:
```python
return render(request, 'index.html', {'meals': meals})


## 🏗️ Installation & Local Setup

Follow these simple steps to spin up **The Maple Plate** locally on your machine:

### 1. Clone the Project

```bash
git clone [https://github.com/your-username/The-Maple-Plate.git](https://github.com/your-username/The-Maple-Plate.git)
cd The-Maple-Plate

```

### 2. Setup Virtual Environment

```bash
# For macOS/Linux
python3 -m venv venv
source venv/bin/activate

# For Windows
python -m venv venv
venv\Scripts\activate

```

### 3. Initialize the Application

```bash
# Check syntax and run basic migrations if needed
python manage.py migrate

# Launch the local development server
python manage.py runserver

```

Once initialized, navigate to `http://127.0.0.1:8000/` in your web browser to view the live interface.

---

## 👨‍💻 Developed By

* **Rishaw Prabhakar**
* *B.Tech in Computer Science & Engineering*
* *Arya College of Engineering and IT*

