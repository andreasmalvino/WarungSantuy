# WarungSantuy

This is a PHP website with MySQL database integration.

## Description

This website serves as a platform for managing a online store. It provides functionalities for both users and administrators.

- Users can browse the menu, place orders, and view their order history.
- Administrators have additional privileges such as managing the menu, processing orders, and view transaction chart.

## Technologies Used

- HTML
- CSS
- JavaScript
- PHP
- MySQL

## Preview

![Uer_Dashboard](/Warung%20Santuy%20Preview/User%20Dashboard.png)

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/andreasmalvino/WarungSantuy.git
   ```

2. Import the database:

   - Create a MySQL database named `warungsantuy`.
   - Import the SQL file `warungsantuy.sql` located in the `database_file` folder.

3. Configure the database connection:

   - Open the `config.php` file located in the `includes` folder.
   - Update the database credentials with your MySQL connection details.

4. Start the web server:

   - Place the cloned repository in the root directory of your web server (e.g., `htdocs` for XAMPP).
   - Start your web server (e.g., Apache).

5. Access the website:

   - Open a web browser and navigate to user side `http://localhost/WarungSantuy`.
   - Open a web browser and navigate to admin side `http://localhost/WarungSantuy/admin`.

## Usage

- Register as a new user or log in if you already have an account.
- Explore the items and add order items.
- Cancel your order in pemesanan menu.
- Change your account detail in akun menu.
- Administrators can log in with their credentials to access the admin side.
- On the admin side, manage the menu, process orders, and view transaction chart.

## Contact

For any inquiries, please contact [andreasmalvii@gmail.com](mailto:adnreasmalvii@gmail.com).
