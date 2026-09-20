# Public Service Queue System 🎟️

An interactive, digital queue management web application built for public service centers, banking halls, and administrative offices to eliminate physical lobby congestion and streamline citizen service workflows.

---

## 🌟 Live Demo & Portfolio
- **Author:** Frans Kurniawan
- **Portfolio:** [https://franskur.github.io](https://franskur.github.io)
- **Role:** Full-Stack PHP Web Developer

---

## 🚀 Key Features

- **Self-Service Ticket Dispenser:**
  - Touchscreen-friendly interface categorizing services (e.g., General Inquiries, Document Submissions, Priority / Senior Citizen Services).
  - Automated timestamping and sequential ticket numbering.

- **Audiovisual Multi-Counter Calling:**
  - Integrated speech synthesis engine for automatic multilingual voice announcements (e.g., *"Number A-042, please proceed to Counter 3"*).
  - Bell chime audio indicators and real-time counter status switching.

- **Real-Time Waiting Room Display Board:**
  - Dynamic visual display showing current served numbers, counter assignments, and estimated waiting queues.
  - Asynchronous status updates without full page reloads.

- **Managerial Performance Dashboard:**
  - Comprehensive operational analytics tracking average customer service times, staff throughput, and peak hour congestion metrics.
  - Daily, weekly, and monthly report generation.

---

## 🛠️ Tech Stack & Architecture

- **Backend:** PHP Native (OOP, MVC Architecture)
- **Database:** MySQL (Normalized relational schema with high-performance indexing for rapid real-time counter querying)
- **Frontend:** HTML5, CSS3, JavaScript (ES6+), Bootstrap 5
- **Audio Integration:** Web Speech Synthesis API & Custom Audio Chimes
- **Security:** Input sanitization, CSRF token validation, and SQL Injection prevention via PDO prepared statements

---

## ⚡ Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/franskur/public-service-queue-system.git
   ```

2. **Database Setup:**
   - Open your MySQL management tool (e.g., phpMyAdmin, HeidiSQL, or MySQL CLI).
   - Create a database named `queue_system_db`.
   - Import the database schema from `database/schema.sql`.

3. **Configure Database Connection:**
   - Rename `config/database.example.php` to `config/database.php`.
   - Update database credentials (`DB_HOST`, `DB_USER`, `DB_PASS`, `DB_NAME`).

4. **Run Application:**
   - Launch your local web server (Laragon, XAMPP, or built-in PHP server):
     ```bash
     php -S localhost:8000 -t public/
     ```
   - Open your browser and navigate to `http://localhost:8000`.

---

## 📄 License & Notes
Designed and developed by **Frans Kurniawan**. Open for portfolio showcase, commercial deployment, and custom business adaptation.
