# Canteen-Ordering-System

A web-based food ordering system designed for college students and canteen administrators to simplify food ordering, management, and pickup scheduling within a campus environment.

🚀 Project Overview

This system allows students to browse food items, place orders, customize meals, select pickup time slots, and track order status in real time. Admins can manage food items, handle incoming orders, and update order status efficiently.

🎯 Key Features

-👨‍🎓 Student Module
Student registration & login (Student/Admin selection during signup)
Personalized dashboard with greeting
Food search and category browsing
Today’s Special section
Add to favorites
Food customization (quantity, special instructions)
Pickup time slot selection
Order placement & confirmation
Order tracking (pending / preparing / ready / completed)
Order history with details
Rating & feedback system
Profile management (name, register number, email, mobile number)
-🧑‍💼 Admin Module
Admin login dashboard
Manage food items:
Add food
Edit food
Delete food
Mark Today’s Special
Manage orders:
View all incoming orders
Update order status (Pending → Preparing → Ready → Completed)
View completed orders summary

🧭 System Flow

-Student Flow
Register/Login → Dashboard → Browse Food → Customize Order → Select Pickup Time → Place Order → Track Status → Rate Order

-Admin Flow
Login → Dashboard → Manage Food → Manage Orders → Update Status → View Completed Orders

📄 Main Pages / Screens

Student Side
Login / Register Page
Student Dashboard
Food Menu Page
Category Filter (All / Breakfast / Lunch / Snacks / Drinks)
Food Details Page
Favorites Page
My Orders Page
Profile Page

Admin Side

Admin Dashboard
Manage Food Page
Manage Orders Page
Completed Orders Page
🛠️ Tech Stack (Suggested)

Frontend: HTML / CSS 
Backend: Python Flask
Database: MySQL
Authentication:Session-based login
Styling: Bootstrap

📦 Features in Detail

🍔 Food Ordering
View food items with images, price, and availability
Add items to cart or order directly
Customize quantity and instructions
Choose pickup time slot
❤️ Favorites
Save preferred food items
Quick order from favorites
📦 Order Management
Real-time order status tracking
Order ID generation
Detailed order history
⭐ Rating System
Rate completed orders
Add feedback/comments
🔐 Roles & Permissions
Role	Access
-Student	Browse food, place orders, view history, rate orders
-Admin	Manage food items, update orders, view analytics
📊 Order Status Lifecycle
Pending → Preparing → Ready for Pickup → Completed
