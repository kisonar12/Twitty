# Twitty

A lightweight user authentication system built with HTML, CSS, and vanilla JavaScript. Users can register, login, and logout with data persistence using browser's localStorage.

Features
User Registration – Create a new account with username, email, and password

User Login – Authenticate with existing credentials

User Dashboard – View your profile information after login

Logout Functionality – Clear session and redirect to login page

Data Persistence – User data stored locally in browser's localStorage

Responsive Design – Works on desktop and mobile devices

Dark Theme UI – Clean, modern dark interface

Technologies Used
HTML5
CSS3
JavaScript (ES6)

Project Structure

├── index.html (or login.html)
├── register.html
├── home.html
├── logout.html
├── style.css
└── README.md
 How to Run Locally
Clone the repository:

bash
git clone https://github.com/your-username/your-repo-name.git
Navigate to the project folder:

bash
cd your-repo-name
Open login.html or register.html in your browser (double-click or use Live Server)

 Note: No build steps or dependencies required – pure HTML/CSS/JS!

How to Use
Register – Go to register page, enter your details, and submit

Login – Use your email and password to access the home page

View Profile – Your information will be displayed on the home page

Logout – Click the logout button to end your session

Limitations
This is a frontend-only demo project. All data is stored in localStorage and is not suitable for production use. For real applications, implement:

Backend server (Node.js, PHP, Python, etc.)

Database (MySQL, PostgreSQL, MongoDB)

Password hashing (bcrypt)

Session management with HTTP-only cookies

Future Improvements
Add password confirmation validation

Prevent duplicate email registrations

Add "Show/Hide Password" toggle

Mask password display on home page

Add form validation error messages (instead of alerts)

License
This project is for educational purposes as part of a web development course.

Author
Kisona Richards
