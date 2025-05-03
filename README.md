Smart Task Scheduler with DSA-Based Optimizations
A full-stack task management system built using Java Spring Boot, MySQL, and Vanilla HTML/CSS/JavaScript. It allows users to create, update, delete, and complete tasks while offering advanced features like undo/redo functionality using custom stack-based logic and real-time search suggestions.

🌟 Features
🔄 Undo/Redo support using custom stack implementation

✅ Task CRUD: Create, read, update, delete tasks

🏁 Mark tasks as completed

🧠 DSA concepts applied for task history and priority handling

📈 View top 3 priority tasks

📋 View completed task history

🔍 Live search: Filter tasks by title while typing

🎨 Clean, minimal frontend using HTML/CSS/JavaScript

🚀 RESTful backend APIs using Spring Boot

🛠️ Tech Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript
Backend	Java, Spring Boot
Database	MySQL
Tools Used	VS Code, Postman, MySQL Workbench

📁 Folder Structure
pgsql
Copy
Edit
SmartTaskScheduler/
│
├── backend/
│   ├── controller/
│   ├── model/
│   ├── repository/
│   ├── service/
│   └── SmartTaskSchedulerApplication.java
│
├── frontend/
│   └── index.html
│
└── README.md
🚀 Getting Started
1️⃣ Backend Setup
Ensure MySQL is running and a database is created.

Update application.properties with your DB credentials.

Run SmartTaskSchedulerApplication.java in your IDE (e.g., IntelliJ, Eclipse, VS Code).

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/taskdb
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
2️⃣ Frontend Setup
Open index.html located in the frontend/ folder using your browser.

The frontend connects to http://localhost:8080/tasks for API calls.
