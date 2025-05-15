# Medical Portal

A Django web app for **Patient** and **Doctor** users. Each user type has a separate dashboard after login.

##  Features

- Signup with profile pic, address, and user type
- Login with redirection to user-specific dashboard
- Custom user model
- UI with custom CSS
- Image upload support (Pillow)

##  Setup

```bash
git clone https://github.com/YOUR_USERNAME/medical-portal.git
cd medical-portal
python -m venv env
env\Scripts\activate  # On Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
Visit: http://127.0.0.1:8000/

## Structure

accounts/: user model, views, forms, templates

media/: uploaded profile pics

static/: CSS, background images

## Tech

Python, Django, SQLite, HTML/CSS

Pillow for image upload
