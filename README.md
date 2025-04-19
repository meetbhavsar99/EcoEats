# EcoEats 🍽️

A smart grocery and recipe management web application designed to help users reduce food waste by tracking food items and suggesting recipes based on available ingredients.

> 🚀 This is a forked version of a collaborative project. I worked on backend optimizations, UI improvements, and integration with the Spoonacular API.

---

## 🔍 Features

- 📦 Add, update, and delete grocery items with expiration tracking
- 🧠 Personalized recipe suggestions using Spoonacular API
- 🧾 Dashboard view to monitor inventory and food waste trends
- 🧼 Clean, responsive UI with Tailwind CSS and template-based design
- 🗃️ User login/register with activity tracking
- 📅 Scheduled notifications for expiring items

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS, HTML, CSS
- **Backend**: Python, Django, SQLite
- **APIs**: Spoonacular API
- **Tools**: Git, GitHub, VS Code

---

## 💻 Getting Started

To run this project locally:

### 1. Clone the repository:

```bash
git clone https://github.com/meetbhavsar99/EcoEats.git
cd EcoEats
```

### 2. Set up Python environment:

```bash
python -m venv env
source env/bin/activate # On Windows: env\Scripts\activate
pip install -r requirements.txt
```

### 3. Run the Django backend:

```bash
python manage.py migrate
python manage.py runserver
```

### 4. Open in browser:

```bash
http://127.0.0.1:8000/
```

## 📁 Folder Highlights

```bash
EcoEats/
├── core/               # Main app logic, models, views, templates
├── static/             # Static assets (CSS, images)
├── templates/          # HTML templates
├── Project/            # Django project config
└── manage.py           # Django entry point
```

## 🙌 Acknowledgment

This project was forked from a team collaboration.

I contributed to:

- Recipe logic and Spoonacular API integration

- Django model improvements

- Dashboard and UI refinements

- Code cleanup and organization

## 📫 Contact

**Meet Bhavsar**  
[GitHub](https://github.com/meetbhavsar99)  
[LinkedIn](https://www.linkedin.com/in/meet-bhavsar-0059ba1b5/)  
📧 [meetbhavsar99@gmail.com](mailto:meetbhavsar99@gmail.com)
