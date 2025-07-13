# pfact_project
# Product Review System - Technical Assignment

This is a REST API for a Product Review System developed as part of the selection process for Info Pfactorial.

## 👥 Features
- Admin users can add/update/delete products.
- Regular users can browse products and post reviews.
- All users can view products and their aggregated ratings.

## 🔗 API Endpoints (Example)
| Method | Endpoint              | Description                     |
|--------|------------------------|---------------------------------|
| GET    | /api/products/         | List all products               |
| POST   | /api/reviews/          | Submit review (user)           |
| GET    | /api/ratings/          | View aggregated product ratings|

## ⚙️ Setup Instructions

```bash
git clone https://github.com/joyas-jose/pfact_project.git
cd pfact_project
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
