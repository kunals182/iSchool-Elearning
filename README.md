# 🎓 iSchool E-Learning Website  

**iSchool** is a modern and responsive **E-Learning Web Application** developed using **HTML, CSS, JavaScript, PHP, and MySQL**.  
It enables students to explore online courses, watch educational videos, and make secure payments for enrollments.  
Admins can manage courses, users, and transactions efficiently from a dedicated dashboard.  

---

## 🌟 Features  
- 🧑‍🎓 User Registration and Login System  
- 📚 Browse and Enroll in Courses  
- 🎥 Integrated Video Lectures (Handled via Git LFS for large files)  
- 💳 Secure Payment Integration  
- 🧑‍🏫 Admin Panel for Managing Courses, Users, and Payments  
- 📱 Responsive Design for Desktop and Mobile  
- 🔍 Search and Filter Courses by Category  
- 🧾 Database Management using MySQL  

---

## 🛠️ Tech Stack  
| Technology | Description |
|-------------|-------------|
| **HTML5 / CSS3** | Frontend design and layout |
| **JavaScript (ES6+)** | Client-side interactivity |
| **PHP** | Backend logic and dynamic content rendering |
| **MySQL** | Database for courses, users, and payments |
| **XAMPP** | Local development environment (Apache + MySQL) |
| **Git LFS** | Handles large video files efficiently |

---

## ⚙️ Installation & Setup  

Follow these steps to run the project locally 👇  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/kunals182/iSchool-Elearning.git

2️⃣ Move to the Project Folder
cd iSchool-Elearning

3️⃣ Copy Folder to XAMPP htdocs Directory

Example path:

C:\xampp\htdocs\project\ELearning

4️⃣ Start XAMPP Server

Run Apache and MySQL from the XAMPP Control Panel.

5️⃣ Import Database

Open phpMyAdmin → http://localhost/phpmyadmin

Create a new database — name it (for example): ischool_db

Import the .sql file included in your project folder under /database/.

6️⃣ Run the Application

Go to your browser and visit:
👉 http://localhost/project/ELearning

🧩 Folder Structure
iSchool-Elearning/
│
├── assets/               # CSS, JS, and image files
├── includes/             # Common PHP includes (header, footer, DB config)
├── admin/                # Admin dashboard and management files
├── user/                 # User dashboard, enrollments, profile
├── video/                # Lecture videos (tracked via Git LFS)
├── database/             # SQL files for MySQL database
├── index.php             # Main landing page
├── about.php             # About page
├── contact.php           # Contact page
├── login.php             # User login
├── register.php          # User registration
├── payment.php           # Payment handling page
└── README.md             # Project documentation

🧠 Database Overview
Table	Description
users	Stores user info (name, email, password, etc.)
courses	Contains course details, descriptions, and prices
enrollments	Tracks user course registrations
payments	Stores transaction and payment status details
🧑‍💻 Author

Kunal Salunkhe
💼 GitHub Profile

📧 yourname@email.com
 (optional)

🌟 Show Your Support

If you found this project helpful or inspiring, please give it a ⭐ on GitHub — it helps others find it too!

🚀 Future Enhancements

✅ Integration with online payment gateways (Razorpay / PayPal)

✅ Course progress tracking and certificates

✅ Live classes via video conferencing API

✅ Email notifications for enrollment and payments

✅ Enhanced admin analytics dashboard
