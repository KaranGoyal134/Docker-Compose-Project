# 🐳 Dockerized MERN Application

This is a **basic MERN (MongoDB, Express, React, Node.js) application** that has been fully containerized using **Docker** and orchestrated with **Docker Compose**.

The goal of this project is to understand:
- How to containerize a full-stack application
- How services communicate inside Docker networks
- How environment variables and service discovery work
- How data persists using Docker volumes

---

## 🧱 Tech Stack

- **Frontend**: React (Vite)
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Containerization**: Docker
- **Orchestration**: Docker Compose

---

## 📁 Project Structure

```text
.
├── mern
│   ├── frontend
│   │   ├── Dockerfile
│   │   └── src/
│   ├── backend
│   │   ├── Dockerfile
│   │   └── routes/
│   └── docker-compose.yml
├── README.md
