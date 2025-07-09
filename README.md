# 📁 Spring Boot AWS S3 File Storage Service

This repository demonstrates how to upload, search, and download files from an AWS S3 bucket using Spring Boot. It includes RESTful APIs for managing user-specific file storage and unit tests for verifying the file operations.

---

## 🚀 Overview

This Spring Boot application provides backend APIs to:

- Upload files to a user-specific directory in an AWS S3 bucket
- Search for files by filename within a user's folder
- Download user files stored in S3

Integration is done using the official AWS SDK (`AmazonS3Client`). The project follows clean code practices and includes unit tests using **JUnit**.

---

## ✨ Features

- ✅ File upload to AWS S3  
- 🔍 Search files by name within user folders  
- ⬇️ Download user-specific files from S3  
- 🧩 User-isolated folder structure (S3 prefixes)  
- 📦 Integration with AWS SDK  
- 🧪 Test-driven development using JUnit  

---

## 🧪 Tech Stack

- **Java 17+**
- **Spring Boot**
- **AWS SDK (S3)**
- **JUnit 5**
- **Maven**

