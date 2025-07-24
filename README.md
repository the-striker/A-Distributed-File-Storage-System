# A-Distributed-File-Storage-System


A simple, secure, and distributed file storage system built with **Java Spring Boot**, **MongoDB**, and **JWT-based authentication**.

---

## 🚀 Features

- ✅ User registration & login with JWT
- ✅ Upload files to local storage
- ✅ Store file metadata in MongoDB
- ✅ User-specific file access (multi-user isolation)
- ✅ Download and list only your files
- ✅ RESTful API design
- 🔐 Secure endpoints with Spring Security (JWT)

---

## 🧱 Tech Stack

- **Java 17**
- **Spring Boot 3+**
- **MongoDB**
- **Spring Security (JWT)**
- **Lombok**
- **Postman** (for API testing)

---

## 📂 Project Structure
src/main/java/com/cloudstorage/filestorage/
├── auth/ → JWT filters & utilities
├── controller/ → REST API endpoints
├── model/ → UserDocument, FileDocument
├── repository/ → MongoDB Repositories
├── service/ → Business logic
└── config/ → Security configuration


