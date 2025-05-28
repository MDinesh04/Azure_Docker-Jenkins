# 🌐 Frontend Deployment with Docker & Jenkins

This project demonstrates how to:

1. Deploy a simple HTML web page using Docker.
2. Automate the build and deployment process using Jenkins.
3. Optionally, host the solution on an Azure VM.

---

## 🧰 Prerequisites

- Docker installed
- Jenkins installed (locally or on an Azure VM)
- Git (optional for source control)
- Ubuntu or any Linux-based OS

---

## 📁 Project Structure


├── Dockerfile

├── index.html

└── README.md

---

## 📦 Docker Instructions

### 1. Build Docker Image

```bash
docker build -t myfrontend .

docker run -d --name web-container -p 80:80 myfrontend

```

Your HTML page is now served by Apache and accessible at:

http://<your-server-ip>


## ☁️ Deploying on Azure
- Launch a Ubuntu VM in Azure.

- SSH into the VM and install Docker + Jenkins.

- Clone this repo and run the above Docker commands or use Jenkins.

- Make sure port 80 is open in the Azure VM’s Network Security Group (NSG).


## 🙌 Made With ❤️ Docker ⚙️ Jenkins ☁️ Azure 🧑‍💻 HTML & Apache
