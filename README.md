# 🍔 Food Delivery App — React JS

A responsive food delivery frontend web application built with **React JS**, containerized using **Docker**, and deployed locally using **Kubernetes (Minikube)**.

## 🌐 Live Demo
👉 https://tomato-food-delivery-akash.netlify.app/

## 🚀 Features
- 🛍️ Browse food items by category
- 🛒 Add to cart and manage orders
- 📱 Fully responsive UI
- ⚡ Fast and smooth user experience

## 🛠️ Tech Stack
- **Frontend:** React JS, Vite
- **Styling:** CSS
- **Containerization:** Docker, Nginx
- **Orchestration:** Kubernetes (Minikube)
- **Version Control:** Git & GitHub

## 🐳 Docker Setup
```bash
# Build Docker image
docker build -t food-delivery-app .

# Run Docker container
docker run -p 3000:80 food-delivery-app
```

## ☸️ Kubernetes Setup
```bash
# Start Minikube
minikube start

# Load Docker image into Minikube
minikube image load food-delivery-app:latest

# Apply Kubernetes deployment
kubectl apply -f k8s/deployment.yaml

# Apply Kubernetes service
kubectl apply -f k8s/service.yaml

# Access the app
minikube service food-delivery-app-service
```

## 📦 Installation & Run Locally
```bash
# Install dependencies
npm install

# Run development server
npm run dev
```

## 📁 Project Structure
```
food-delivery-app/
├── k8s/
│   ├── deployment.yaml
│   └── service.yaml
├── src/
├── public/
├── Dockerfile
├── .dockerignore
├── .gitignore
└── README.md
```

## 👨‍💻 Author
**Akash Aralikatti**
- GitHub: https://github.com/akashak0717/food-delivery-app.git
- LinkedIn: www.linkedin.com/in/akasharalikatti0717