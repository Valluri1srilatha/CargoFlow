# 🚛 FleetSync - Smart Logistics & Fleet Management System

FleetSync is a full-stack logistics management web application built using **Spring Boot**, **MySQL**, and **HTML/JavaScript**.  
It enables seamless coordination between **Admins** and **Users** for managing transport orders, drivers, trucks, and carriers — all in one place.

---

## 🧭 Overview

FleetSync is designed to simplify logistics workflows:

- Users can place and track transport orders.  
- Admins can manage drivers, trucks, and carriers efficiently.  
- Automatic **email notifications** keep users informed at every stage of their shipment journey.  

---

## 👥 Login Roles

### 🔹 User
- Place new transport orders.  
- Track order details and current status.  
- Receive automatic **email updates** when:
  - Order is **placed** ✅  
  - Truck is **loaded** 🚚  
  - Truck is **unloaded** 🏭  
  - Order is **completed** 📦  

### 🔹 Admin
- Manage all **Drivers**, **Trucks**, **Carriers**, and **Orders**.  
- Assign available trucks and carriers to drivers.  
- Update loading/unloading information for any order.  
- Automatically change truck status from `Available` → `In Use` when assigned.  

---

## 🌟 Key Features

### 👤 User Features
- Secure login and registration.  
- Simple order placement form.  
- Real-time order tracking.  
- Automatic **email notifications** with order updates.  

### 🧑‍💼 Admin Features
- Dashboard for managing:
  - Drivers  
  - Trucks  
  - Carriers  
  - Orders  
- Update loading and unloading details.  
- Assign trucks and carriers dynamically.  
- Truck status automatically changes when assigned.  

---

## 📧 Email Notifications

FleetSync automatically sends emails to users during major order events:

| Event | Trigger | Example Subject |
|--------|----------|----------------|
| Order Placed | When user places an order | `Order #1234 Confirmed - Thank You for Choosing FleetSync!` |
| Loading Started | Admin updates loading info | `Order #1234 - Loading Started` |
| Unloading Completed | Admin updates unloading info | `Order #1234 - Unloading Completed` |
| Status Update | Any manual change in status | `Order #1234 - Status Updated` |

Emails are sent using **Spring Boot Mail (JavaMailSender)** with clean HTML templates.

---

## ⚙️ Tech Stack

### 🧩 Backend
- **Java 17+**
- **Spring Boot**
- **Spring Data JPA (Hibernate)**
- **Spring Boot Mail**
- **MySQL Database**
- **RESTful API Architecture**

### 💻 Frontend
- **HTML5**, **CSS3**, **JavaScript (Vanilla JS)**
- **AJAX** for asynchronous calls  
- **Responsive UI** for both Admin and User dashboards

---

## 🗂️ Project Structure

