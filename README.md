# women--empowerment

# 🌸 Women Empowerment Platform

A full-stack web application built with *React + Vite, **Tailwind CSS, and **Supabase* to support women's growth through stories, events, mentorship, and resources.

---

## 🚀 Features

### 🔐 User Authentication
- Email/password signup and login
- Form validation & session management
- Protected routes and user-specific views
- Secure profile integration with Supabase Auth

### 📚 Dynamic Content
- *Stories*: Submit success stories for review and publication
- *Events*: Register in real-time with capacity tracking
- *Resources*: Searchable library with download tracking
- *Community*: Interactive features based on auth status

### 🗄 Backend Infrastructure (Supabase)
- Fully relational database schema
- Secure *Row Level Security (RLS)* policies
- Database triggers and functions
- Real-time data updates and syncing
- User data isolation

### ⚙ Database Operations
- CRUD operations for all entities
- Automatic attendee updates, download logs
- Data relationships (FKs between users, events, etc.)
- Advanced filtering for resources and stories

### 🎯 Interactive Features
- Event registration with live capacity checks
- Story submission and moderation
- Download tracking for resources
- User-specific content visibility

---

## 🛠 Technologies Used

- *Frontend*: React, Vite, Tailwind CSS
- *Backend*: Supabase (PostgreSQL, Auth, Realtime)
- *Deployment*: Vercel (optional)

---

## 🧑‍💻 Getting Started

### Prerequisites
- Node.js & npm
- Supabase project with credentials

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/women-empowerment-app.git
cd women-empowerment-app
npm install
npm run dev

You can view this project live in : https://womenempowermentfsd.netlify.app/
