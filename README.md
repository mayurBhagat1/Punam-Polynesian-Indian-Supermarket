---
title: "Punam Polynesian & Indian Supermarket Website ( Coming Soon will be uploaded at the end of October or the start of November)"
author: "Mayur Bhagat"
---

# Introduction

The **Punam Polynesian & Indian Supermarket Website** is designed to support both **customers** and **staff**.  
The main website currently runs from the **backend folder**, which contains all active features.  
In the future, the **frontend folder** will host a modern React-based website for customers.  

---

# Purpose of the Website

- To allow customers to explore Polynesian & Indian supermarket products online.  
- To let members place bookings and manage their accounts.  
- To give staff the ability to manage products, customers, and bookings in one system.  

---

# Features

## For Customers
- **Public Product Page**: Everyone can view products and categories without logging in.  
- **Member Login for Orders**: Only registered members can place bookings/orders.  
- **Order Tracking Page**: Logged-in customers can see their orders, track status (pending, complete, cancelled), and cancel within 30 seconds if needed.  
- **Contact Page**: Easy way to ask questions or get support.  
- **Mobile-Friendly**: The site adapts to phones and tablets.  

## For Staff
- **Product Management**: Add, edit, or remove products.  
- **Booking/Order Management**: View and process customer orders.  
- **Customer Management**: Maintain customer accounts and details.  
- **Database Connection**: All products, orders, and users are safely stored.  

---

# How the Website Works

1. **Visitors** can browse the product page without logging in.  
2. To **place a booking/order**, the visitor must **log in as a customers**.  
3. Once logged in, customers can request products and track their orders.  
4. Orders appear in the **Order Tracking Page** where customers can check progress.  
5. **Staff members** log in to manage products, bookings, and customer accounts.  

---



# Future Plans

- Build a **React frontend** for a smoother customer experience.  
- Add **online payment options**.  
- Create **staff dashboards** with reports and analytics.  
- Add **loyalty programs** and **special offers**.  

---

# Summary

The **Punam Polynesian & Indian Supermarket Website** provides:  
- A **public product page** open to everyone.  
- A **customers-only system** for placing bookings and orders.  
- A working **Order Tracking page** for customers to view and manage their orders.  
- Tools for **staff** to manage products, bookings, and customers.  

Currently, the website lives in the **backend folder**, but soon the **frontend folder** will include a React project to make the customer experience even better. 

## 🛠️ Technologies Used

- **Node.js + Express.js** → powers the backend, handles routing, orders, login, etc.  
- **EJS (Embedded JavaScript Templates)** → used for rendering web pages dynamically (header, footer, orders page, etc.).  
- **MySQL / SQL Database** → stores products, users, and orders securely.  
- **CSS (Custom Styling)** → used for design and responsive pages.  
- **Session-based Authentication** → login system for customers & staff (no shopping cart yet, but login is required for ordering).  
- **Frontend (Planned)**: React will be added in the `frontend` folder for a modern user experience.  
- **Deployment-ready** → can be hosted on cloud servers (AWS, Azure, etc.).  

---

## 🚀 Getting Started

1. **Install Requirements**  
   - Make sure you have **Node.js** and **MySQL** installed.  

2. **Clone or Download the Project**  
   - Extract the project folder from the zip file.  

3. **Install Dependencies**  
   ```bash
   cd backend
   npm install
   ```  

4. **Set Up the Database**  
   - Create a database in MySQL.  
   - Import the provided SQL file (if included) or set up tables for **users, products, and orders**.  
   - Update the database connection settings in the project’s config file (e.g., `db.js` or `.env`).  

5. **Run the Project**  
   ```bash
   npm run dev -w backend dev
   ```  
   - The backend will start on **http://localhost:8080/**.  

6. **Access the Website**  
   - Open your browser and go to `http://localhost:8080/`.  
   - You can browse products without logging in.  
   - To place or track orders, you must **log in as a customer**.  

---


# ⚠️ Disclaimer

By downloading, installing, or testing this website, you do so at your own risk.  
The authors and maintainers are not responsible for any problems, damages, or data loss.

You are **not allowed** to edit, copy, or share the code for commercial or public use.  
This website is only for testing, learning, or personal use **unless you are authorised by the creator, Mayur Bhagat**.

**Copyright:**  
All rights of this website belong to **Mayur Bhagat, Punam Polynesian & Indian Supermarket**.





⚠️ License

This project is licensed. Please review the license terms before modifying or redistributing any part of the codebase.

© 2025  Mayur Bhagat  Punam Polynesian & Indian Supermarket
