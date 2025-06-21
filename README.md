# Dorkari Toythya (দৰকাৰী তথ্য)

**Dorkari Toythya** is a simple and accessible web app built with FastAPI, designed to help elderly citizens in Assam quickly access essential government services — like electricity bill payment, property tax, and more — all in one place.

## 🌟 Features

- 🔗 One-click access to Assam government portals (APDCL, GMC, etc.)
- 📍 Google Maps integration to locate government offices
- 🌐 FastAPI backend with simple HTML frontend
- 🐳 Dockerized and Kubernetes-ready
- 🧓 Accessibility-focused design

## 🚀 Technologies Used

- Python + FastAPI
- Jinja2 Templates
- Docker
- Kubernetes (Okteto/KubeSail compatible)

## 🛠️ Run Locally

```bash
git clone https://github.com/your-username/dorkari-toythya.git
cd dorkari-toythya
pip install -r requirements.txt
uvicorn app.main:app --reload
```

## 🐳 Docker

```bash
docker build -t your-dockerhub-username/dorkari-toythya .
docker run -p 8000:8000 your-dockerhub-username/dorkari-toythya
```

## ☸️ Kubernetes Deployment

Apply the manifests inside `kubernetes/`:

```bash
kubectl apply -f kubernetes/
```

## 📷 Screenshot

![Dorkari Toythya UI](https://via.placeholder.com/800x400.png?text=Dorkari+Toythya+Homepage)

---

Built with ❤️ for Assam’s senior citizens.
