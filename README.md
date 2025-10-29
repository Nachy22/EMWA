# 🎟️ Monolith Web Application — Event Management System

This project is a **monolithic web application** developed as part of our Software Design and Architecture coursework.  
It provides a platform for users to register, log in, create events, RSVP to events, and receive real-time updates.  
The system includes **authentication**, **user roles**, **real-time functionality**, and integration with modern tools.

---

## 🧠 Project Overview

The **Monolith Event Management System** is a single-architecture web application where all functionalities—frontend, backend, and database—are tightly integrated.  
The app was built with **Elysia.js**, **Prisma ORM**, and **Neon PostgreSQL**, and includes WebSocket-based real-time updates.

---

## ⚙️ Features

- **Authentication & Authorization**
  - Secure JWT-based authentication
  - Role-based access (Admin, User)
- **Event Management**
  - Create, update, and delete events
  - RSVP to events
  - View all registered users
- **Real-Time Updates**
  - Events and RSVPs update live using WebSockets
- **Error Handling & Validation**
  - All API routes include validation and detailed error responses
- **API Documentation**
  - Swagger integrated for testing and exploring API endpoints

---

## 🛠️ Setup Instructions

### 1. Install Dependencies
```bash
bun install
# EMWA
