# 🏨 Booking System – Scalable Microservice-based Reservation & Payment Backend

## 🚀 Overview

The **Booking System** is a **robust and scalable backend** designed to efficiently handle reservations and payments. Built using **NestJS**, it follows a **microservice architecture** and leverages **RabbitMQ** for seamless inter-service communication, ensuring high scalability and flexibility.

This system is ideal for applications that require **secure booking management**, whether for hotels, events, or other services.

## 🎯 Features

✅ **Microservice Architecture** – Modular design for scalability and maintainability.  
✅ **RabbitMQ for Messaging** – Ensures efficient communication between services.  
✅ **Secure Authentication** – Implemented using **Passport.js**.  
✅ **Efficient Database Management** – Uses **MongoDB** for structured storage.  
✅ **Testing & Reliability** – Fully tested using **Jest** to ensure system stability.  
✅ **Containerization** – Uses **Docker** for easy deployment and portability.  
✅ **Cloud Deployment** – Hosted on **Google Cloud** and **AWS** for high availability.

## 🛠️ Tech Stack

| Technology            | Purpose                                                  |
|-----------------------|----------------------------------------------------------|
| **NestJS**            | Framework for building efficient and scalable backend apps |
| **RabbitMQ**          | Message broker for seamless communication between services |
| **Passport.js**       | Authentication middleware for secure user management    |
| **MongoDB**           | NoSQL database for flexible data storage               |
| **Jest**              | Testing framework for unit and integration tests        |
| **Docker**            | Containerization for consistent deployment             |
| **Google Cloud & AWS**| Cloud infrastructure for deployment and scalability    |

## 📦 Installation

### 🔧 Prerequisites
- **Node.js** (v18+)
- **pnpm** (for dependency management)
- **MongoDB** (local or cloud instance)
- **RabbitMQ** (for message queuing)
- **Docker** (for containerization)
- **Google Cloud or AWS** (for cloud deployment, optional)

### 📥 Clone the Repository
```sh
git clone https://github.com/ahmedGHANIM327/system-reservations-server.git
cd booking-system
````

### 📌 Install Dependencies
```sh
pnpm install
````

### ▶️ Run the Development Server Using Docker compose
```sh
docker compose up -d
````

