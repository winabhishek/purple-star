# Purple Star - Online Stationery and Book Store

**Purple Star** is a web application designed to sell stationery and book-related products online. It provides an intuitive interface for users to browse, search, and purchase items, while offering an admin dashboard for managing products and categories.

## Features

- **User Interface**: 
  - Browse and search for products.
  - View detailed descriptions of each item.
  - Contact page for user inquiries.

- **Admin Dashboard**:
  - Add, update, and delete products.
  - Manage categories for better organization.
  
- **Database Integration**:
  - Stores product details, user accounts, and orders in a MySQL database.

- **Technology Stack**:
  - Frontend: HTML, CSS, Bootstrap, JavaScript (including Popper.js).
  - Backend: PHP.
  - Database: MySQL.

## Folder and File Structure

- **index.php**: Homepage showcasing products.
- **navbar.php**: Navigation bar for easy browsing.
- **add_product.php**: Add new products to the inventory.
- **categories.php**: Manage product categories.
- **admin_dashboard.php**: Admin panel for monitoring and updates.
- **book.php**: Dedicated page for books.
- **text-book.php**: Page for textbook-related listings.
- **single.php**: Product detail page.
- **contact.php**: Contact form for user queries.
- **login.php**: User login page.
- **logout.php**: Logout functionality.
- **dbconnection.php**: Database connection file.
- **login_register.sql**: SQL file for creating and managing the database structure.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/winabhishek/purple-star.git
2. Set up the database:

Import the login_register.sql file into your MySQL database.
Configure database credentials in the dbconnection.php file.
3. Start the server:

Use a local server like XAMPP or WAMP.
Place the project files in the htdocs directory.
Access the application:

Open a web browser and navigate to http://localhost/purple-star.
