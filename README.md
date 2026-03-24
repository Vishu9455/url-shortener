# URL Shortener 🚀

A scalable URL shortening service built using Java and Spring Boot that converts long URLs into short links and redirects users efficiently.

---

## ✨ Features
- Convert long URLs into short links
- Redirect short URL to original URL
- Track number of clicks (analytics)
- REST API based backend system

---

## 🛠 Tech Stack
- Java
- Spring Boot
- MySQL
- Spring Data JPA
- REST APIs

---

## 📌 API Endpoints

### 🔹 Shorten URL
POST /api/shorten

Request Body:
https://example.com

Response:
abc123

---

### 🔹 Redirect to Original URL
GET /api/{shortUrl}

Example:
GET /api/abc123

Response:
https://example.com

---

## ⚙️ How to Run the Project

1. Clone the repository:
git clone https://github.com/YOUR_USERNAME/url-shortener.git

2. Open project in IntelliJ IDEA

3. Configure MySQL database in application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/url_db
spring.datasource.username=root
spring.datasource.password=yourpassword

4. Create database:
CREATE DATABASE url_db;

5. Run the application

6. Test APIs using Postman

---

## 📸 Sample Workflow

1. Send POST request to shorten URL  
2. Receive short code  
3. Use GET request to redirect  

---

## 📈 Future Improvements
- Add Redis caching for faster response
- Custom short URLs
- Frontend UI
- Deployment on cloud

---

## 👩‍💻 Author
Vaishnavi Singh

---

## ⭐ If you like this project, give it a star!
