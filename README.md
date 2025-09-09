🚔 Crime Record Management System (CRMS)
A case study project built using MySQL to simulate real-world crime tracking and suspect profiling. The system manages and analyzes crime records through interlinked tables and advanced SQL operations.

✨ Features:
📂 Relational Database Design with Crimes and Suspects tables (300+ entries each)
🔗 Joins (INNER, LEFT, RIGHT, FULL) for multi-table queries
🧩 Nested Queries & Aggregations for crime statistics and profiling
👁️ Views for simplified data access
⚡ Indexing for faster query performance
⚙️ Stored Procedures & Functions to automate tasks
🔔 Triggers for enforcing business rules
🔄 Cursors for handling record-by-record operations

📂 Database Structure:
Crime_Record_Management_System/
│── Crimes Table       # Stores details of crimes (crime_id, type, date, location, officer_id, suspect_id, etc.)  
│── Suspects Table     # Stores suspect details (suspect_id, name, age, address, history, etc.)  
│── Officers Table     # (Optional) Officer details for crime assignments  

🚀 Getting Started:
1) Clone the repository: git clone https://github.com/your-username/crime-record-management-system.git
2) Import database:
-Open MySQL Workbench / CLI
-Run the SQL script provided in /scripts/crms.sql
3) Test queries
-Explore joins, views, triggers, and stored procedures included in the project

🛠️ Technologies Used:
MySQL – Database and SQL operations
SQL Concepts – Joins, Views, Indexing, Stored Procedures, Triggers, Cursors
