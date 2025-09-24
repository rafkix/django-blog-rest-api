Tushundim ✅ — siz `README.md` faylini shunday formatda xohlaysizki, unda faqat kerakli joylarda `bash` yoki `python` code bloklari bo‘lsin, qolgan yozuvlar oddiy markdown matn bo‘lsin. Oldingi variantimda hamma joy `bash` ichiga tushib ketayotgandek bo‘libdi.

Mana siz uchun toza va to‘liq `README.md` 👇

````markdown
# 📝 Django Blog REST API

A fully featured **Blog REST API** built with **Django** and **Django REST Framework (DRF)**.  
It supports posts, comments, categories, tags, likes, and user profiles.  
The API is fully documented with **Swagger** and **Redoc**.

---

## 🚀 Features
- User authentication & profiles  
- Create, update, delete blog posts  
- Categorize and tag posts  
- Commenting system  
- Like system for posts  
- Interactive API documentation (Swagger & Redoc)  

---

## 🛠 Tech Stack
- [Python 3.x](https://www.python.org/)  
- [Django](https://www.djangoproject.com/)  
- [Django REST Framework](https://www.django-rest-framework.org/)  
- [drf-yasg](https://drf-yasg.readthedocs.io/) (Swagger & Redoc docs)  
- SQLite (default, can be switched to PostgreSQL/MySQL)  

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/django-blog-rest-api.git
   cd django-blog-rest-api
````

2. Create and activate virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:

   ```bash
   python manage.py migrate
   ```

5. Create a superuser (for admin panel):

   ```bash
   python manage.py createsuperuser
   ```

6. Run the server:

   ```bash
   python manage.py runserver
   ```

---

## 📌 API Endpoints

### 🔹 Posts

* `GET /api/posts/` → List all posts
* `POST /api/posts/` → Create a new post
* `GET /api/posts/{id}/` → Retrieve a post
* `PUT /api/posts/{id}/` → Update a post
* `DELETE /api/posts/{id}/` → Delete a post

### 🔹 Comments

* `POST /api/posts/{id}/comments/` → Add a comment to a post

### 🔹 Likes

* `POST /api/posts/{id}/likes/` → Like a post

### 🔹 Categories

* `GET /api/categories/` → List categories
* `POST /api/categories/` → Create a category

### 🔹 Tags

* `GET /api/tags/` → List tags
* `POST /api/tags/` → Create a tag

### 🔹 Profiles

* `GET /api/profiles/{id}/` → Get user profile
* `PUT /api/profiles/{id}/` → Update user profile

---

## 📖 API Documentation

* Swagger UI → [http://127.0.0.1:8000/swagger/](http://127.0.0.1:8000/swagger/)
* Redoc → [http://127.0.0.1:8000/redoc/](http://127.0.0.1:8000/redoc/)

---

## 🔮 Future Improvements

* JWT authentication (login/register endpoints)
* Pagination & search
* Deploy to Heroku / Railway
* Frontend integration (React / Vue)

---

## 👨‍💻 Author

Created by [Your Name](https://github.com/rafkix) ✨
```
