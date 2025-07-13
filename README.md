# 📝 Flask Blog Platform

A full-featured blogging platform built using **Flask**, supporting user authentication, admin controls, rich text editing, and commenting.  
**Live Demo:** [https://blog-6-j6be.onrender.com/](https://blog-6-j6be.onrender.com/)

---

## 🚀 Features

- 🔐 **User Authentication:** Secure registration and login system with hashed passwords.
- 🛠️ **Admin Controls:** Only admin (User ID = 1) can create, edit, and delete blog posts.
- 📰 **Blog Posts:** View all posts, read individual posts, and see associated comments.
- 💬 **Commenting System:** Registered users can leave comments on blog posts.
- 🖋️ **Rich Text Editing:** CKEditor integration for post creation and editing.
- 👤 **User Avatars:** Gravatar integration for profile images.
- 🎨 **Responsive Design:** Uses Bootstrap for clean, mobile-friendly UI.
- 📄 **Extra Pages:** Includes **About** and **Contact** sections.

---

## 🧰 Tech Stack

- **Backend:** Python, Flask  
- **Frontend:** HTML, Bootstrap, Flask-Bootstrap  
- **Database:** SQLite (via SQLAlchemy ORM)  
- **Authentication:** Flask-Login, Werkzeug  
- **Forms:** WTForms  
- **Other Integrations:**  
  - CKEditor (rich text editor)  
  - Gravatar (profile images)

---

## 📁 Project Structure

```
📦 your-project/
├── main.py # Main Flask application
├── forms.py # WTForm classes
├── templates/ # HTML templates
├── static/ # CSS, JS, image files
├── instance/
│ └── posts.db # SQLite database file
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```

---

## ⚙️ Getting Started

### 🔧 Prerequisites
- Python 3.x
- pip

### 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/your-flask-blog.git
   cd your-flask-blog
   ```
2. **Install dependencies**
   ```bash
    pip install -r requirements.txt
    Set environment variables
   ```

3. In your terminal or .env file:
  ```
  FLASK_KEY=your-secret-key
  DATABASE_URI=sqlite:///instance/posts.db
  ```
4. Run the application
  ```bash
  python main.py
  Open in browser
  Visit: http://127.0.0.1:5000/
  ```

