# SkyLearn - Django LMS

SkyLearn is a modern, full-featured **Learning Management System (LMS)** built with **Django**. It allows instructors to create courses, manage students, and track progress, while students can enroll in courses, access learning materials, and track their own progress.

---

## 🏆 Features

* **User Authentication:** Sign up, login, password reset, and profile management.
* **Courses Management:** Create, edit, and delete courses (admin/instructor side).
* **Student Dashboard:** View enrolled courses, progress, and upcoming assignments.
* **Email Notifications:** Sends emails for registration, updates, and reminders (Gmail SMTP).
* **Responsive UI:** Fully responsive design for desktop and mobile.
* **Environment Configuration:** Easy `.env` setup for sensitive credentials.

---

## 🚀 Tech Stack

* **Backend:** Django, Python
* **Frontend:** HTML, CSS, JavaScript, Bootstrap
* **Database:** SQLite (default), can be switched to PostgreSQL
* **Email:** Gmail SMTP / Console backend for development
* **Version Control:** Git & GitHub

---

## ⚡ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Siddscell/SkyLearn.git
   cd SkyLearn
   ```

2. **Create virtual environment:**

   ```bash
   python -m venv venv
   venv\Scripts\activate   # Windows
   source venv/bin/activate # macOS/Linux
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Setup environment variables:**

   * Copy `.env.example` to `.env` and fill in your credentials:

     ```bash
     cp .env.example .env   # macOS/Linux
     copy .env.example .env # Windows
     ```

5. **Apply migrations:**

   ```bash
   python manage.py migrate
   ```

6. **Run the development server:**

   ```bash
   python manage.py runserver
   ```

7. Open your browser at `http://127.0.0.1:8000/` to see SkyLearn in action.

---

## 📂 Directory Structure

```
SkyLearn/
├─ manage.py
├─ SkyLearn/
│  ├─ settings.py
│  ├─ urls.py
│  └─ wsgi.py
├─ apps/
│  └─ ...
├─ templates/
├─ static/
├─ .env
└─ requirements.txt
```

---

## ⚙️ Configuration

* **Email:** Set up Gmail SMTP in `.env` for production email sending.
* **Debug Mode:** `DEBUG=True` for development, `False` for production.
* **Secret Key:** Use a strong, unique `SECRET_KEY` in `.env`.

---

## 💻 Usage

* **Admin Panel:** `http://127.0.0.1:8000/admin/`
* **Instructor:** Create courses and manage content.
* **Student:** Enroll in courses and track progress.

---

## 📝 License

This project is **open-source** and available under the MIT License.

---

## 📫 Contact

**Author:** Siddhant Patil
**Email:** [siddhantpatil560@gmail.com](mailto:youremail@example.com)
**GitHub:** [Siddscell](https://github.com/Siddscell)
