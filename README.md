# Inventory-Management-System
🧾 Project Description:
The Inventory Management System is a Python-based desktop application designed to help store or warehouse managers keep track of products, stock levels, and transactions. It supports CRUD operations (Create, Read, Update, Delete), low-stock alerts, sales reports, and secured access through user authentication. The system comes with a user-friendly Graphical User Interface (GUI) using Tkinter.

🎯 Core Features:
🔐 User Authentication:
Secure login system with username and password.

Role-based access (e.g., admin, staff – optional).

📦 Product Management:
Add new products (name, category, price, quantity).

Edit existing product details.

Delete products.

📊 Inventory Tracking:
Real-time view of inventory levels.

Low-stock alerts (e.g., quantity < threshold).

Search/filter products by name or category.

🧾 Reporting:
Sales summary report.

Export inventory/sales data to CSV.

View daily/weekly/monthly activity (optional).

✅ Data Validation:
Prevent empty or invalid inputs.

Confirmation before deleting or editing records.

🎨 GUI (Tkinter):
Easy-to-navigate interface.

Forms for login, product management, and reports.

💾 Data Storage:
Use SQLite (lightweight built-in database).

Optional: Use CSV or JSON for data backup.

🛠️ Technologies Used:
Language: Python 3.x

GUI: Tkinter

Database: SQLite

Extras: Pandas (for reports), CSV module, JSON (for backup)

🧪 Example Use Cases:
->A store employee logs in and adds 50 units of “USB Cable”.

->The system alerts when “Batteries” drop below 10 units.

->Manager generates a CSV of monthly sales and inventory.

