# movie-stream
# 🎬 Full Stack Movie Ticket Booking Website

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Made With MERN](https://img.shields.io/badge/stack-MERN-blueviolet)](#)
[![Deployment](https://img.shields.io/badge/Live-Demo-brightgreen)](https://your-live-demo-link.com)

This is a complete **Full Stack Movie Ticket Booking Application** built using the **MERN Stack (MongoDB, Express.js, React, Node.js)**. Users can browse movies, select seats, and book tickets with real-time updates. Includes an **Admin Dashboard** for managing content.

---

## 🚀 Features

### 🧑‍💻 User Functionality
- Sign up / Log in using **Clerk** (Email, Social, Phone login)
- **Multi-session support**: Easily switch between multiple accounts
- Browse and explore movies
- Seat selection and secure booking
- Automated booking confirmation & email reminders (**Inngest**)
- **10-minute seat-hold system** for failed payments

### 🛠️ Admin Panel
- Add / Edit / Delete Movies
- View and manage all user bookings
- Upload movie posters and trailers using **Multer**

---

## 🧰 Tech Stack

| Technology     | Role                         |
|----------------|------------------------------|
| MongoDB        | NoSQL Database                |
| Express.js     | Backend framework             |
| React.js       | Frontend UI                   |
| Node.js        | Server runtime                |
| Clerk          | Authentication & session mgmt |
| Inngest        | Background jobs, email tasks  |
| Multer         | File upload handling          |

---

## 📧 Background Email Automation

With **Inngest**, the app:
- Sends booking confirmations
- Sends movie reminder emails before showtime
- Notifies users when new movies are added

---

## 💳 Seat Holding Logic

If a payment fails or is canceled:
- Seats are **held for 10 minutes**
- Automatically released if payment isn’t completed

---

## 🖼️ Screenshots

### Home Page
![Homepage](screenshots/homepage.png)

### Movie Booking Page
![Booking](screenshots/booking.png)

### Admin Dashboard
![Admin](screenshots/admin.png)

> Add your actual screenshots in a `/screenshots` folder and replace the paths above.

---

## 🌐 Live Demo

🔗 [Click here to try the live app](https://your-live-demo-link.com)

---

## 📁 Project Structure

