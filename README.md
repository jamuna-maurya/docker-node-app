# 🚀 Dockerized Node.js App

##  Project Description

This is a simple Node.js application built using Express and containerized using Docker.
It demonstrates how to create, build, and run a Docker container for a backend application.

---

##  Tech Stack

* Node.js
* Express.js
* Docker

---

##  Project Structure

```
docker-node-app/
│── app.js
│── package.json
│── Dockerfile
│── .dockerignore
```

---

##  Setup & Installation

###  Clone the Repository

```
git clone <your-repo-link>
cd docker-node-app
```

---

###  Install Dependencies (Optional - for local run)

```
npm install
```

---

###  Run App Locally

```
node app.js
```

Open in browser:

```
http://localhost:3000
```

---

##  Docker Setup

### 1️⃣ Build Docker Image

```
docker build -t node-docker-app .
```

---

### 2️⃣ Run Docker Container

```
docker run -d -p 3000:3000 node-docker-app
```

---

###  Access Application

```
http://localhost:3000
```

---

## Output


```
Hello from Dockerized Node.js App 🚀
```

<img width="2843" height="1511" alt="doc png" src="https://github.com/user-attachments/assets/62240b25-34f3-4583-a0be-b7c992f26135" />

---

##  What I Learned

* Creating a Node.js Express server
* Writing a Dockerfile
* Building Docker images
* Running containers
* Port mapping

---

##  Author

jeny

---
