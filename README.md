# Whois Lookup 🌐

A web application for domain WHOIS lookups, built with **Angular** on the frontend and **Django REST Framework** on the backend.

## 🚀 Live Demo

Try the live version:  
🔗 [https://whois-lookup.pewepskei.dev](https://whois-lookup.pewepskei.dev)

## 🧱 Tech Stack

- **Frontend**: [Angular](https://github.com/pewepskei/whois-angular-wrapper)
- **Backend**: [Django REST Framework](https://github.com/pewepskei/whois-django-wrapper)  
- **Containerization**: Docker + Docker Compose

## 📦 Requirements

- [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/)

## 🛠️ Setup Instructions

Clone the repository (including submodules if any):

```bash
git clone --recurse-submodules https://github.com/pewepskei/whois-lookup.git
cd whois-lookup
```

> If you've already cloned the repo without `--recurse-submodules`, run:
> ```bash
> git submodule update --init --recursive
> ```

Build and run the app:

```bash
docker compose up --build -d
```

Once the containers are running, access the application at:

- 🌐 **Frontend**: [http://localhost:5000](http://localhost:5000)
- 🔌 **Backend API**: [http://localhost:8000](http://localhost:8000)

## 📝 Notes

- The Angular frontend runs on port `5000`.
- The Django backend runs on port `8000`.
- Make sure those ports are free before starting the containers.

---

