# 🍽️ Multi-Cuisine Interactive Hotel Menu System

This project is a responsive and interactive hotel menu system developed using **HTML**, **CSS**, **JavaScript**, **PHP**, and **MySQL**. It allows users to browse dishes by cuisine, adjust quantities, and place orders — which are then stored in a MySQL database.

---

## 📌 Features

- 🧭 Landing page with animated logo
- 🍛 Tab-based menu interface with multi-cuisine support
- 🛒 Cart functionality with quantity control
- 🧾 Order submission with customer name and table number
- 💾 Orders stored in MySQL database and logged in a text file
- 🧑‍💼 Admin panel to view all submitted orders

---

## 🛠 Technologies Used

- HTML5, CSS3
- JavaScript (localStorage, dynamic UI)
- PHP (form handling and MySQL connection)
- MySQL (database for storing orders)
- XAMPP (local development environment)

---

## 📁 Folder Structure


---

## 🔗 How to Run the Project Locally

1. **Install XAMPP** and start `Apache` + `MySQL`
2. Place the project folder (`GUSTO`) into `C:/xampp/htdocs/`
3. Open [phpMyAdmin](http://localhost/phpmyadmin) and:
   - Create a database called `cafe_gusto`
   - Import the SQL script (`SQL.sql.txt`)
4. Open your browser and go to:  
   👉 `http://localhost/GUSTO/interface.html`

---

## ✅ To Place an Order:

- Navigate through the cuisines
- Add items to your cart
- Go to the cart page
- Enter your name and table number
- Click **Place Order** and **Submit to Database**

Orders will be saved to:
- `orders` table in MySQL
- `cart.txt` file in the project folder

---

## 🔒 Admin Access

To view orders, open:  
👉 `http://localhost/GUSTO/admin_panel.php`

---

## ✨ Future Enhancements

- User login and authentication
- Real-time kitchen dashboard
- Online payment gateway
- Responsive admin dashboard
- Order status tracking

---

## 👨‍💻 Contributors

- [Your Name Here]
- [Your Roll Number]
- [Your College]

---

## 📜 License

This project is created for academic purposes. You are free to use and modify it with attribution.
