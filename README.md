# 📝 MyBlog – Full-Stack Blogging Platform

A full-featured blog application built with Django, Django REST Framework, PostgreSQL, and Docker. Supports JWT-based authentication, user roles (Admin, Author, Subscriber), nested comments, post categories/tags, and markdown-based content editing with TOC generation.

---

[▶️ Watch the demo](assets/demo-hero-page.mp4)

---

## 🔗 Repositories

| Layer      | Repository                                                                 |
|------------|----------------------------------------------------------------------------|
| Backend 🐍 | [MyBlog API (Django)](https://github.com/tomislav98/blog_backend_django.git)     |
| Frontend ⚛️ | [MyBlog UI (React)](https://github.com/tomislav98/blog_frontend_react.git)     |




---

## 🚀 Features

- ✍️ Rich-text blog posts with markdown + auto-generated Table of Contents (TOC)
- 🔒 JWT-based user authentication (`rest_framework_simplejwt`)
- 👤 Custom user model with roles: Admin, Author, Subscriber
- 💬 Nested comments with moderation (Pending / Approved / Spam)
- 🧩 Categories, Tags, and filtering
- 📊 Post views and like tracking
- 🐳 Dockerized development setup
- 🌐 Optional React frontend


---



## ✅ To Do

- [ ] Complete frontend integration
- [ ] Add automated testing (Pytest, DRF test client)
- [ ] Add CI/CD with GitHub Actions
- [ ] Add deployment configuration (Render, Railway, etc.)
- [ ] Improve API documentation
- [ ] Add user profile and settings page
- [ ] Optimize Docker setup for production



---

## ⚙️ Tech Stack

- **Backend:** Django, Django REST Framework
- **Authentication:** JWT (`rest_framework_simplejwt`)
- **Database:** PostgreSQL
- **Containerization:** Docker & Docker Compose
- **Frontend:** React (optional)
- **Styling:** Tailwind CSS / Bootstrap (optional)

---

### 📦 Installing dependencies

It is recommended to use a virtual environment:

```bash
python -m venv .venv
source venv/bin/activate  # Linux/macOS
# or
.\venv\Scripts\activate   # Windows PowerShell

pip freeze > requirements.txt
