

```markdown
# 📝 Django Notes App

A fully functional **Notes Web Application** built using Django and Docker, designed for simplicity, clean architecture, and production-readiness. This project demonstrates containerized Django development with MySQL integration using Docker Compose.

---

## 🚀 Features

- ✍️ Create, update, and delete notes
- 📁 Organize notes by title and timestamp
- 🐳 Dockerized for easy setup and deployment
- 🔄 Persistent MySQL database using volumes
- 🔐 Environment-variable-based configuration
- 🚀 Gunicorn as a production-ready WSGI server

---

## 🛠 Tech Stack

| Layer        | Technologies                |
|-------------|-----------------------------|
| Backend      | Django (Python)             |
| Database     | MySQL                       |
| Web Server   | Gunicorn                    |
| Containerization | Docker, Docker Compose  |
| Dev Tools    | Git, GitHub                 |

---

## 📁 Project Structure

```

djangonotes-app/
├── app/                     # Django project directory
│   ├── notes/               # Django app for notes
│   ├── manage.py
├── Dockerfile               # Docker image build instructions
├── docker-compose.yml       # Multi-container orchestration
├── requirements.txt         # Python dependencies
├── .env                     # Environment configuration
└── README.md

````

---

## ⚙️ Getting Started

### 🔧 Prerequisites

- Docker & Docker Compose installed
- Git installed

---

### 🚀 Running the App

```bash
# Clone the repository
git clone https://github.com/Lahari-Haribabu/djangonotes-app.git
cd djangonotes-app

# Create a .env file with database credentials
cp .env.example .env   # or create manually

# Build and run the app
docker compose up --build
````

### 📂 .env File Example

Create a `.env` file in the root directory:

```env
DB_NAME=notes_db
DB_USER=root
DB_PASSWORD=yourpassword
DB_HOST=db
DB_PORT=3306
```

---

## 📦 Docker Details

* `web` container runs Django with Gunicorn
* `db` container runs MySQL with persistent volume
* MySQL data persists in `data/` volume even after container shutdown

---

## 🔐 Security & Environment

* All sensitive credentials are stored in `.env` (never committed to Git)
* `.gitignore` and `.dockerignore` ensure clean Git history and lean images

---

## 📌 Future Enhancements

* 🔑 User authentication and login
* 🏷️ Tag-based note organization
* 📱 API integration (Django REST Framework)
* 🌐 Frontend with React or Bootstrap
* ⚙️ CI/CD setup with GitHub Actions or Jenkins
* ☁️ Deployment on AWS or other cloud platforms

---

## 🙋‍♀️ Author

**Lahari Haribabu**
🚀 Passionate about backend, DevOps, and building scalable applications.
📬 [Connect on LinkedIn](https://www.linkedin.com/in/lahari-haribabu)

---

## ⭐️ Show your support!

If you like this project:

* Star the repo ⭐
* Fork it 🍴
* Share it 📢

```


