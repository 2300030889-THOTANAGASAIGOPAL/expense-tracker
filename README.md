📊 Expense Tracker
A full-stack expense tracker web application to manage daily income and expenses, built with React (Vite) frontend, Spring Boot backend, and MySQL as the database.

🛠️ Tech Stack
Frontend: React (Vite), Tailwind CSS

Backend: Spring Boot (Java), Spring Security, Spring Data JPA

Database: MySQL

Authentication: JWT, Email verification (Gmail/SendGrid)

PDF Export: iTextPDF (or similar)

🚀 Features
🔐 User Signup, Login, and Forgot Password

📥 Add, edit, delete income and expenses

📊 View expenses by category/date

📄 Export expense report to PDF

📧 Email verification and password reset

👥 User-specific data handling

📂 GitHub integrated with frequent commits

📸 Screenshots
(You can add screenshots here of your login page, dashboard, PDF export, etc.)

⚙️ Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/expense-tracker.git
2. Backend Setup (Spring Boot)
Open in Eclipse or IntelliJ

Configure application.properties:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/expense_db
spring.datasource.username=your_username
spring.datasource.password=your_password
Run ExpenseTrackerApplication.java

3. Frontend Setup (React with Vite)
bash
Copy
Edit
cd frontend
npm install
npm run dev
🧪 API Endpoints
Method	Endpoint	Description
POST	/api/auth/signup	Register a new user
POST	/api/auth/login	Login with credentials
POST	/api/auth/forgot	Send reset password email
GET	/api/expenses	Get all expenses (user-wise)
POST	/api/expenses	Add a new expense
GET	/api/export/pdf	Export expenses to PDF

📦 Folder Structure
bash
Copy
Edit
project-root/
│
├── backend/             # Spring Boot app
│   ├── src/main/java/…
│   └── resources/
│
├── frontend/            # React (Vite) app
│   ├── src/
│   └── public/
✅ To Do
 Authentication

 Email verification

 PDF export

 Graphs and charts (future)

 Mobile responsive design (future)
