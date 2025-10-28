

## 🗂️ Repository Overview

**Repository Name:** [mdnaimul404/Portfolio-Personal](https://github.com/mdnaimul404/Portfolio-Personal)

**Description:**
This repository hosts a personal portfolio website built using **Python** and **Django**. It serves as a digital resume, showcasing the developer's skills, projects, and achievements. The portfolio is designed to be responsive and user-friendly, providing an interactive experience for visitors.

---

## 🧰 Technologies Used

* **Backend:** Python with Django framework
* **Frontend:** HTML, CSS
* **Database:** SQLite (as indicated by the `db.sqlite3` file)
* **Server Management:** Django's built-in `manage.py` utility

---

## ✅ Key Features

* **Responsive Design:** Ensures optimal viewing experience across various devices.
* **Project Showcase:** Highlights personal projects with descriptions and links.
* **Skills Display:** Lists technical skills and proficiencies.
* **Contact Form:** Allows visitors to get in touch through a contact form.

---

## 🔧 Setup Instructions

To run the Personal Portfolio locally:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/mdnaimul404/Portfolio-Personal.git
   cd Portfolio-Personal
   ```

2. **Set Up a Virtual Environment:**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations:**

   ```bash
   python manage.py migrate
   ```

5. **Create a Superuser (for admin access):**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the Development Server:**

   ```bash
   python manage.py runserver
   ```

7. **Access the Application:**
   Open a browser and navigate to `http://127.0.0.1:8000/` to view the application.

---

## 📌 Notes

* Ensure that all dependencies listed in `requirements.txt` are installed.
* The project appears to be in the early stages, with potential for further development and feature additions.
* For production environments, consider configuring a more robust database system like PostgreSQL and setting up proper security measures.
* This project is developed for educational purposes as part of a Computer Graphics course.You are free to view and learn from the source code.
