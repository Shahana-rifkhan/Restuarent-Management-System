# Restuarent-Management-System
The website will serve as a digital platform where customers can explore the facilities and services offered by the restaurant. The system will also facilitate staff operations, allowing restaurant employees to manage reservations, respond to customer inquiries, and process payments online. The application will cater to three types of users: Admin, restaurant staff, and customers. This strategic move is expected to position Signature Cuisine as a leader in the hospitality industry by offering a seamless and interactive online experience.

## Installation

Follow these steps to set up the project on your local machine:

### Prerequisites

- **XAMPP**: Ensure you have XAMPP installed on your machine. You can download it from [here](https://www.apachefriends.org/index.html).
- **PHP**: Make sure PHP is set up correctly on your XAMPP server.
- **MySQL**: Ensure MySQL is running on XAMPP for database management.

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/YourUsername/Restuarent-Management-System.git

2. **Move the project files**: Move the cloned project folder to the `htdocs` directory inside your XAMPP installation directory (usually found in `C:\xampp\htdocs` on Windows).

3. **Start the XAMPP server**: Open the XAMPP control panel and start the Apache and MySQL modules.

4. **Configure the database**:

- Open your browser and go to `http://localhost/phpmyadmin/`.
- Create two new database called `restaurant` and `accounts`.
- Import the `restaurant.sql` files located in the root directory of the project into your `restaurant` database.
- Import the `accounts.sql` files located in the root directory of the project into your `accounts` database.

5. **Configure the database connection**:

- Open the config.php file located in the root directory.
- Update the following lines with your database details:
  ```bash
  $servername = "localhost";
  $username = "root"; // Replace with your MySQL username
  $password = ""; // Replace with your MySQL password
  $dbname = "restaurant"; // Ensure this matches your database name

6. **Access the website**:
- Open your browser and go to `http://localhost/Restuarent-Management-System/index.php` to view the home page.

## Admin Credentials
Use the following credentials to log in as an admin:
  - Username: `admin@gmail.com`
  - Password: `admin`

These credentials can be updated in the admin panel and database as needed.

## Usage
- Admin Login: Admins can log in through `admin_page.php`.
- User Registration: Users can register through `register_form.php`.
- Reservation System: Users can make reservations through `reservation.php`.
- Complaint Management: Admins and users can manage complaints through various forms and views.

## Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Please ensure your code follows the project's coding standards.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
```bash
This `README.md` file should provide clear instructions for setting up and using your Complaint Management System. You can modify it as needed to fit any additional details specific to your project.
