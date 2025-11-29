
# MySQL + phpMyAdmin (Docker Compose)

This project provides a simple and ready-to-use Docker Compose setup for running:
- **MySQL 8**
- **phpMyAdmin**
  
It's designed for learning, development, or local testing.

---

##  Features

- MySQL 8 database with persistent storage  
- phpMyAdmin web UI for database management  
- Environment variables stored safely in `.env`  
- Automatic container startup with `docker compose up -d`  
- Clean, minimal configuration

---
Clone this repository and: docker compose up -d

### 4. Access phpMyAdmin
Open in your browser:

 `http://localhost:8080`

Login details:

- **Server:** mysql  
- **Username:** root  
- **Password:** (value from your `.env`)  

---

##  Volumes

MySQL data is stored in a Docker volume so your database persists even after container restarts.

---






