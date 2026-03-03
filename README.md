# Online-Medical-Store-using-MySQL-Database
he Online Medical Store is a web-based application developed to facilitate the online purchase of medicines and healthcare products. This system allows customers to browse medicines, search for products, upload prescriptions (if required), and place orders conveniently from their homes. The backend database is managed using MySQL.

📌 Project Overview

The Online Medical Store is a web-based application that allows users to purchase medicines and healthcare products online. The system provides an easy-to-use interface for customers and an administrative dashboard for managing medicines, inventory, and orders.

The backend database is built using MySQL, ensuring secure data storage, efficient data management, and smooth order processing.

🎯 Objectives

1.Provide a convenient platform to buy medicines online.

2.Maintain medicine records using MySQL database.

3.Automate inventory and order management.

4.Securely store customer and prescription data.

🚀 Features
👤 User Module

1.User Registration & Login

2.Search Medicines

3.Add to Cart

4.Upload Prescription

5.Place Orders

View Order History

🛠️ Admin Module

1.Add / Update / Delete Medicines

2.Manage Stock

3.View & Manage Orders

4.Manage Users

5.Generate Sales Reports

🛠️ Technologies Used
Technology	Purpose
HTML	Frontend Structure
CSS	Styling
JavaScript	Client-side Interaction
PHP / Python	Backend Logic
MySQL	Database Management
Apache / XAMPP	Server Environment
🗄️ Database Structure
1️⃣ Users Table

user_id (Primary Key)

name

email

password

phone

address

2️⃣ Medicines Table

medicine_id (Primary Key)

name

category

price

stock_quantity

expiry_date

3️⃣ Orders Table

order_id (Primary Key)

user_id (Foreign Key)

order_date

total_amount

order_status

4️⃣ Order_Details Table

order_detail_id (Primary Key)

order_id (Foreign Key)

medicine_id (Foreign Key)

quantity

price

5️⃣ Prescription Table

prescription_id (Primary Key)

user_id (Foreign Key)

image_path

upload_date

status
