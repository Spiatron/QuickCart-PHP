
# QuickCart-PHP 🛒

![PHP](https://img.shields.io/badge/PHP-7.4%2B-777BB4?style=flat-square&logo=php)
![MySQL](https://img.shields.io/badge/MySQL-5.7%2B-4479A1?style=flat-square&logo=mysql)
![Bootstrap](https://img.shields.io/badge/Bootstrap-4.0-7952B3?style=flat-square&logo=bootstrap)
![Apache](https://img.shields.io/badge/Apache-2.4-D22128?style=flat-square&logo=apache)

QuickCart is an e-commerce platform offering seamless shopping experiences with features like product browsing, cart management, and easy purchasing. The admin panel facilitates efficient product management and user administration.

## 🌟 Features

- 🛍️ **User Interface:**
  - Browse products by categories.
  - Search functionality for quick product discovery.
  - Shopping cart for managing selected items.
  - User registration and authentication.
  - Order history and tracking.

- 🔧 **Admin Panel:**
  - Add, edit, and delete products.
  - Manage product categories.
  - View and process customer orders.
  - User management capabilities.

## ⚙️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Spiatron/QuickCart-PHP.git
   ```

2. **Move files to XAMPP `htdocs` directory:**

   Copy the `QuickCart-PHP` folder to the `htdocs` directory of your XAMPP installation. Typically, this is located at `C:\xampp\htdocs` on Windows.

3. **Start Apache and MySQL services:**

   Open the XAMPP control panel and start the Apache and MySQL services.

4. **Import the database:**

   - Open your web browser and navigate to `http://localhost/phpmyadmin`.
   - Create a new database named `quickcart`.
   - Import the `techhunter.sql` file located in the project root into the `quickcart` database.

5. **Configure database connection:**

   - Open the `config.php` file located in the `src` directory.
   - Update the database connection parameters to match your MySQL configuration:

     ```php
     define('DB_SERVER', 'localhost');
     define('DB_USERNAME', 'your_username');
     define('DB_PASSWORD', 'your_password');
     define('DB_NAME', 'quickcart');
     ```

6. **Access the application:**

   - User Interface: Navigate to `http://localhost/QuickCart-PHP/public/index.php`.
   - Admin Panel: Navigate to `http://localhost/QuickCart-PHP/public/admin.php`.

## 🧑‍💻 Usage

- **User Interface:**
  - Register a new account or log in with existing credentials.
  - Browse products, add items to the cart, and proceed to checkout.
  - View order history and manage account details.

- **Admin Panel:**
  - Log in with admin credentials.
  - Manage products, categories, and user accounts.
  - Process and update order statuses.

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request detailing your changes.

