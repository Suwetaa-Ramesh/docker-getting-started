# 🚀 Docker Tutorial Project

A simple goal-tracking application with a Node.js backend and a React frontend, all wrapped up with Docker for an easy and consistent development environment.

## 🛠 Prerequisites

Make sure you have the following installed:

- 🐳 Docker
- 🐳 Docker Compose

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone this repo
cd docker-getting-started


```

### 2. Create Environment Files in env directory

```bash
create a backend.env file with:

MONGODB_USERNAME=your-username
MONGODB_PASSWORD=your-password
MONGODB_URL=your-mongodb-url
MONGODB_NAME=your-database-name

create a mongo.env file with:

MONGO_INITDB_ROOT_USERNAME=username
MONGO_INITDB_ROOT_PASSWORD=password
```

### 3. Build and Start the Services

```bash
docker-compose up --build

```

### 4. Access the Application

Backend: `http://localhost`
Frontend: `http://localhost:3000`

## 🐳 Docker Commands

- **Build Images**: `docker-compose build`
- **Start Services**: `docker-compose up`
- **Stop Services**: `docker-compose down`
- **View Containers**: `docker ps`
