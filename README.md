# Django Blog

A simple and fully functional blog application built using Django.

## Features
- User authentication (Register, Login, Logout)
- Create, Read, Update, and Delete (CRUD) blog posts
- Commenting system
- Category-based filtering
- Responsive UI with Bootstrap

## Installation
### Prerequisites
Make sure you have **Python 3.x** and **pip** installed on your system.

### Clone the Repository
```sh
git clone https://github.com/John-developer-18/django-blog.git
cd django-blog
```

### Create a Virtual Environment
```sh
python -m venv env
source env/bin/activate  # For macOS/Linux
env\Scripts\activate    # For Windows
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

### Apply Migrations
```sh
python manage.py migrate
```

### Create a Superuser
```sh
python manage.py createsuperuser
```
Follow the prompts to set up an admin account.

### Run the Server
```sh
python manage.py runserver
```

Open your browser and go to [http://127.0.0.1:8000](http://127.0.0.1:8000)

## Usage
- Visit `/admin/` to manage posts and users.
- Users can sign up, log in, and create blog posts.
- Posts can be categorized and commented on.

## Folder Structure
```
├── django-blog/
│   ├── blog/              # Main app with models, views, and templates
│   ├── static/            # CSS, JavaScript, and images
│   ├── templates/         # HTML templates
│   ├── manage.py          # Django management script
│   ├── db.sqlite3         # SQLite database (if used)
│   ├── env/               # Virtual environment (excluded in .gitignore)
```

## Contributing
1. Fork the project.
2. Create your feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contact
For any questions, feel free to reach out:
- **GitHub**: [@John-developer-18](https://github.com/John-developer-18)
- **Email**: your-email@example.com
