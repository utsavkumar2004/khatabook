📒 Khatabook Web 
A secure and modern web-based version of the popular Khatabook app, built using Node.js, Express.js, MongoDB, and modern web technologies.
This project digitizes small business bookkeeping, helping users manage transactions, customers, and reports from any device with internet access — without being tied to a mobile app.

🚀 Features
🔹 Core Khatabook Functionalities
Customer Management → Add, edit, delete, and search customers.

Ledger Book → Maintain debit/credit entries with running balance.

Transaction History → Track all past transactions for each customer.

Payment Reminders → Send SMS/Email reminders for pending dues.

PDF & Excel Export → Download transaction reports.

🔹 Added Features (Better than Mobile App)
Multi-Device Access → Works on desktop, tablet, or mobile browsers.

Cloud Backup → All data stored securely in MongoDB Atlas with encryption.

Role-Based Access Control (RBAC) → Owners, accountants, and staff can have different permissions.

Two-Factor Authentication (2FA) → Optional OTP-based login for extra security.

Advanced Search & Filters → Search by name, phone, date, or transaction type.

Bulk Upload Transactions → Upload CSV/Excel for faster entry.

Dark/Light Mode → Switch themes for comfort.

🔹 Security Improvements
End-to-End Encryption for Sensitive Data (AES-256).

Hashed Passwords with bcrypt.

Rate Limiting & Brute Force Protection.

CSRF & XSS Protection with Helmet.js and express-validator.

HTTPS Enforcement for secure data transfer.

Activity Logs for tracking all user actions.

🛠 Tech Stack
Frontend

HTML5, CSS3, JavaScript

EJS Template Engine

Tailwind CSS for responsive UI

Backend

Node.js

Express.js

MongoDB Atlas

Mongoose ORM

Security & Utilities

bcrypt.js for password hashing

jsonwebtoken (JWT) for authentication

Helmet.js for securing HTTP headers

express-rate-limit for DDoS protection

multer for file uploads

📂 Project Structure
Khatabook-Web/
│
├── public/           # Static assets (CSS, JS, images)
├── views/            # EJS templates
├── routes/           # Route definitions
├── models/           # Mongoose schemas
├── controllers/      # Business logic
├── middlewares/      # Authentication & security
├── config/           # Database and environment config
├── package.json
└── server.js         # App entry point

# Start the server
npm start

👨‍💻 Author
Utsav Kumar
📧 Email: utsavbhy@gmail.com
🔗 LinkedIn: linkedin.com/in/utsav-kumar-a07054219
💻 GitHub: github.com/utsavkumar2004
