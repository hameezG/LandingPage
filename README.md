# Landing Page with Lead Capture Form

This project is a responsive landing page for online courses that demonstrates an interactive design with a lead capture form. The form collects user information (Full Name, Email, and Phone Number) and saves it to a MySQL database using a PHP backend running on XAMPP. After a successful submission, users are redirected to a thank-you page.

## Project Structure

LandingPage/ ├── index.html # Main landing page ├── save_lead.php # PHP script to save form data to MySQL ├── thankyou.php # Thank you page after form submission ├── css/ │ └── style.css # Custom CSS styles └── img/ # Folder containing images used in the project

## Features

- **Responsive Design:** Built with Bootstrap and custom CSS for optimal viewing on desktop, tablet, and mobile.
- **Interactive Navigation:** Includes a navigation bar with call-to-action buttons.
- **Lead Capture Form:** Users can subscribe by entering their full name, email address, and phone number.
- **PHP Backend:** The form data is processed by `save_lead.php` and stored in a MySQL database.
- **Thank You Page:** After submission, users are redirected to `thankyou.php` which confirms their submission.

## Prerequisites

- [XAMPP](https://www.apachefriends.org/download.html) (or another local PHP/MySQL environment)
- Basic knowledge of HTML, CSS, PHP, and MySQL
- Git (for version control)

## Setup Instructions

1. **Clone the Repository:**
   Open your terminal or Git Bash and run:
   ```sh
   git clone https://github.com/hameezG/LandingPage.git
2.	Place the Project in XAMPP: Copy the cloned repository into your XAMPP htdocs folder. For example: 
o	On Windows: C:\xampp\htdocs\LandingPage
o	On macOS/Linux: /Applications/XAMPP/htdocs/LandingPage
3.	Set Up the MySQL Database: 
o	Open XAMPP Control Panel and start Apache and MySQL.
o	Navigate to http://localhost/phpmyadmin.
o	Create a new database named lead_capture.
o	Create a table named leads using the following SQL: 
o	CREATE TABLE leads (
o	    id INT AUTO_INCREMENT PRIMARY KEY,
o	    name VARCHAR(255) NOT NULL,
o	    email VARCHAR(255) NOT NULL,
o	    phone VARCHAR(20) NOT NULL
o	);
4.	Configure PHP (if needed): The default XAMPP configuration is used in save_lead.php (username: root, password: ""). Modify these credentials if you have changed them.
5.	Run the Project Locally: Open your browser and navigate to: http://localhost/LandingPage/index.html
Version Control and Deployment
•	Git Commits: 
o	Initial Commit: Added basic HTML structure.
o	CSS Styling Commit: Added and refined CSS for a modern, responsive layout.
o	JavaScript & PHP Functionality Commit: Added PHP backend and form submission handling.
•	GitHub Repository:
The project is pushed to https://github.com/hameezG/LandingPage.git.
Note: This project uses PHP and a MySQL database, so it must be hosted on a server that supports PHP (like XAMPP). GitHub Pages only supports static files, so you cannot deploy this backend functionality on GitHub Pages.
License
This project is open-source and free to use.
Acknowledgements
•	Bootstrap for responsive design.
•	XAMPP for local development.
•	GitHub for version control and repository hosting.

---

Feel free to adjust any sections as needed. Simply add this `README.md` file to your project's root directory, commit it to Git, and push to your repository.

