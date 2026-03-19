# 🚗 CarGallery — Interactive Car Showcase Platform

---

## 📖 Project Overview

CarGallery is a full-stack web application where users can explore cars, upload their own vehicles, interact through comments and likes, and manage their own content.

The project initially started as a simple university course assignment. The initial goals were only to:

* Add cars to a database
* Display cars in a simple interface

However, the project was gradually expanded and evolved into a much more advanced web platform. During approximately **4–5 months of development**, the project was redesigned and improved multiple times.

The final result is a **portfolio-level full-stack application** demonstrating strong practical experience in backend development, database management, security practices, and advanced frontend design.

This project was developed independently, with the entire development process carried out by me.

---

## 🧰 Tech Stack

**Frontend:**

* HTML
* CSS (Advanced UI design, animations, responsive layout)
* JavaScript (Advanced DOM manipulation, dynamic UI, AJAX)

**Backend:**

* PHP (MySQLi)

**Database:**

* MySQL (managed via phpMyAdmin)

---

## ## 📄 License & Usage

This project is a proprietary, portfolio-based application developed entirely by the author.

The source code is **not open for public use**.
Copying, modifying, distributing, or reusing any part of this codebase without explicit permission is strictly prohibited.

This repository is shared for **demonstration and evaluation purposes only**.

---

### 💼 Commercial Use & Access

The source code may be provided under specific conditions:

* For **employers or recruiters** who want to review the full implementation
* For **clients or individuals** interested in purchasing and adapting the project for their own use

If you are interested in accessing or licensing this project, please contact:

📩 **[your email here]**

---

### 🌐 Live Demo

🔗 [your-live-site-link]


---

## 📸 Screenshots

```plaintext
/screenshots
```

(Project visuals will be added here)

---

## 🖼️ Car Gallery

The main gallery page displays all vehicles uploaded by users.

**Features:**

* Grid-based car cards
* Smooth animations and visual effects
* Like counters
* Sorting options (Newest / Most liked / My Cars)
* Edit/Delete controls for content owners

---

## 💬 Comment System

Each vehicle has its own fully interactive comment section.

**Features:**

* Add / Edit / Delete comments
* Like comments
* Sorting (Newest / Most liked)
* Pagination system

AJAX is actively used across the system to provide dynamic updates without page reload:

* Comment loading
* Comment interactions
* Car updates and image changes

This significantly improves performance and user experience.

---

## 🛡️ Moderation System

The system includes moderation features to maintain platform integrity:

* User banning system
* Moderation history tracking
* Admin notes
* Activity logging

---

## 🏗️ System Architecture

### 📁 Project Structure

```plaintext
CAR_GALLERY/
│
├── index.php                # Main landing page (homepage UI & hero sections)
├── README.md                # Project documentation and guide
│
├── assets/
│   ├── style.css            # Main stylesheet (layout, animations, UI design)
│   ├── script.js            # Global JavaScript (UI logic, DOM, interactions)
│   └── images/              # Static assets used in UI
│
├── auth/
│   ├── login.php            # User login system (authentication & session start)
│   ├── register.php         # User registration (validation & account creation)
│   ├── logout.php           # Logout (session destroy)
│   ├── banned.php           # Restricted access page for banned users
│   └── auth_check.php       # Middleware (session control & route protection)
│
├── cars/
│   ├── add_car.php          # Add new car (image upload + validation)
│   ├── edit_car.php         # Edit existing car (owner/admin control)
│   ├── delete_car.php       # Delete car (permission-based)
│   ├── list_car.php         # Car listing (sorting & filtering)
│   ├── car.php              # Car detail page (comments & interactions)
│   └── like_car.php         # Like system (AJAX-based)
│
├── comments/
│   └── like_comment.php     # Comment like system (AJAX handling)
│
├── profile/
│   ├── profile.php          # User profile page (UI + account management)
│   ├── profile_action.php   # Backend logic for profile actions
│   ├── change_email.php     # Email update (validation + logging)
│   └── change_password.php  # Password update (secure hashing)
│
├── config/
│   └── db.php               # Database connection (MySQLi configuration)
│
└── uploads/                # User-uploaded images (car storage)
```

---

## 🗄️ Database Structure

The application uses a relational MySQL database.

**Main tables:**

* users
* cars
* comments
* comment_likes
* car_likes
* notifications
* ban_history
* car_delete_log
* car_update_history
* user_change_logs

These structures handle:

* authentication
* content management
* user interactions
* moderation
* activity tracking

---

## 🔐 Security Implementation

🛡️ **SQL Injection Protection**
All queries use prepared statements.

🔑 **Authentication Control**
Login required for critical actions:

* adding cars
* editing cars
* deleting cars
* commenting
* liking

👮 **Authorization**
Users can only modify their own content.

📁 **Image Upload Security**

* extension validation
* MIME type checks
* file size limits

🔐 **Session Security**
Sessions are securely handled to prevent unauthorized access.

🧠 **Cyber Security Relevance**

The project applies real-world Web Application Security practices:

* SQL injection prevention
* authentication systems
* authorization checks
* secure session management
* file upload validation

Even “fsociety” would have to pass multiple layers before getting anywhere.

---

## 📊 Database & Data Handling

The project demonstrates:

* relational database design
* table relationships
* CRUD operations
* data validation
* structured data storage

SQL is primarily used for backend logic and data management.

---

## 📚 What I Learned From This Project

**Frontend, Backend, Database Design, Authentication Systems & Web Security**

This project represents a full-stack development process built from scratch.

On the frontend side, I developed interactive and user-focused interfaces using HTML, CSS, and JavaScript. With approximately **2 years of prior experience**, and an additional **4–5 months of intensive development in this project**, I significantly improved my practical skills and reached an advanced level in frontend development, especially in UI behavior, responsiveness, and dynamic interaction handling.

On the backend side, I built the full application logic, handling client–server communication, data flow, and database interactions. I implemented CRUD operations, request validation, and ensured data integrity across the system.

I designed a relational database structure, established table relationships, and managed structured data efficiently. I also implemented authentication (login, session management) and authorization (access control) systems to enforce user-based permissions.

From a security perspective, I applied core Web Security principles directly in the application, including SQL injection prevention using prepared statements, session security, and secure file upload validation (MIME type, extension, and size checks).

This project enabled me to independently develop a complete, production-style web application and strengthened my ability to approach real-world problems with a structured, scalable, and security-focused mindset.

---

## 🎯 Project Purpose

* practice full stack development
* gain backend experience
* understand relational databases
* implement authentication systems
* apply web security techniques

The project transformed theoretical knowledge into real-world development experience.

---

## 👨‍💻 Developer

**Bedirhan Elçik**

MIS (Management Information Systems) Student

Full Stack Development | Web Security | Database Systems
