
## 📦 Requirements

* Python 3.9
* Node.js
* React

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Lahari-Haribabu/djangonotes-app.git
cd djangonotes-app
```

### 2. Build the app with Docker

```bash
docker build -t notes-app .
```

### 3. Run the app

```bash
docker run -d -p 8000:8000 notes-app:latest
```

---

## 🌐 Set up Nginx (optional, for reverse proxy)

To expose the app publicly through port 80:

```bash
sudo apt-get update
sudo apt install nginx
```

Then configure Nginx as a reverse proxy pointing to `localhost:8000`.

---

## 📄 About

A simple notes application for learning full-stack Dockerized app deployment.

---

## 🛠️ Resources

* [`README`](#)
* Docker
* React
* Django
* Nginx

---

## 📊 GitHub Stats

| Metric      | Count         |
| ----------- | ------------- |
| ⭐ Stars     | You decide 😉 |
| 👀 Watchers | You decide 😉 |
| 🍴 Forks    | You decide 😉 |

---

## 🤝 Contributors

* [@Lahari-Haribabu](https://github.com/Lahari-Haribabu)

---





