🎓 Skillshare — Skill Exchange Platform
Skillshare is a modern web application designed to connect people who want to learn with those who want to teach. Users can post skills they wish to offer or learn, explore skill listings, connect with others, and chat through an integrated messaging system.

✨ Features
🔒 Secure User Authentication

Register and log in safely

Password hashing with password_hash()

Session management

Role-based access for Users/Admins

🧰 Skill Management

Post skills to offer or request

Upload images for each skill

Categorize (Programming, Design, Music, etc.)

Search & filter by category and keywords

View detailed skill info

🤝 Connect with Others

Send and receive connection requests

Accept or decline requests

Track all your connections

💬 Live Chat

Direct messaging between connected users

Read/unread message status

Auto-refresh for new chats

Clean, simple chat interface

📊 Admin Dashboard

View real-time stats and insights

Manage users, skills, connections & messages

Monitor reports with interactive charts

Update system settings easily

🚀 Getting Started
✅ Prerequisites
XAMPP (Apache, PHP 7.4+, MySQL)

Modern web browser (Chrome, Firefox, Edge)

Git for cloning

⚙️ Installation
Clone the Repository

bash
Copy code
git clone https://github.com/rajatsinghten/Skillshare.git
cd Skillshare
Setup XAMPP

Start Apache and MySQL via the XAMPP Control Panel.

Place the Skillshare folder in xampp/htdocs/.

Create the Database

Open phpMyAdmin

Create a new database named: skillshare

Import the schema:

pgsql
Copy code
database/Skillshare Database .sql
Configure Database Connection
Edit includes/db.php:

php
Copy code
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "skillshare";
Setup Admin Account

Visit: http://localhost/Skillshare/admin/setup_admin.php

Default admin credentials:

Email: admin@skillshare.com

Password: admin123

Run the App

User Site: http://localhost/Skillshare/pages/index.php

Admin Panel: http://localhost/Skillshare/admin/admin_login.php

📂 Project Structure
bash
Copy code
Skillshare/
├── admin/          # Admin panel files
├── assets/         # CSS, JS, images
├── database/       # SQL schema
├── includes/       # PHP includes
├── pages/          # Main app pages
├── uploads/        # User uploads
└── README.md       # This file
🎯 How to Use
👤 For Users

Sign Up: Create an account.

Post Skills: Offer or request skills.

Search: Find skills or people.

Connect: Send connection requests.

Chat: Message connections in real-time.

Manage: Update your profile and skills.

🛡️ For Admins

Login: Use admin credentials.

Monitor: Track site stats.

Manage: Users, skills, connections, and chats.

Analyze: Check reports and analytics.

Configure: Update system settings.

🧩 Built With
Backend:

PHP 7.4+

MySQL

mysqli (prepared statements)

Frontend:

HTML5 & CSS3 (Grid, Flexbox)

JavaScript + AJAX

Font Awesome (icons)

Chart.js (charts)

Security:

SQL Injection Prevention

XSS Protection

CSRF Protection

Bcrypt password hashing

File upload validation

🗂️ Database Overview
Core Tables:

users — Profiles & logins

skills — Posted skills

messages — Connection requests

chat_messages — User chats

reviews — (Planned) Skill reviews

Relationships:

One user → many skills

One user → many connections

Connected users → messages

Skills → multiple reviews

🤝 Contributing
Contributions are welcome!

Fork this repo

Create a new branch: git checkout -b feature/NewFeature

Commit: git commit -m 'Add feature'

Push: git push origin feature/NewFeature

Open a Pull Request

📄 License
This project is licensed under the MIT License — see LICENSE.

🐞 Known Limitations
Upload size limited by PHP settings

Chat relies on auto-refresh (WebSocket planned)

Images aren’t yet optimized

🔮 Roadmap
Real-time notifications 🔔

Video calls 📹

Ratings & reviews ⭐

Advanced search filters 🔍

Mobile app 📱

Email alerts 📧

Multi-language support 🌐

Premium payments 💳

📬 Contact
📧 Email: pranavi4n3@gmail.com
🐙 GitHub: @pranaviii04

