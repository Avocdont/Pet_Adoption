Pet Adoption Website

This is a simple PHP & MySQL-based pet adoption website where users can browse pets, send adoption requests, and admins can manage those requests.


Project Members:

Abud, Ervin Clint
Alidon, Mediya
Jaboli, Shean Alvin
Regana, John Adrian


Project Structure

index.php       → Homepage showing all available pets  
adopt.php       → Handles adoption requests from users  
padpt.sql       → SQL file to set up the database  


How to Run the System Locally:

Step 1: Download and Install XAMPP
- If you don’t have XAMPP installed yet, download it from:
  https://www.apachefriends.org/index.html
- Install it and launch the XAMPP Control Panel

Step 2: Clone the Repository to htdocs
- Open Command Prompt
- Navigate to the XAMPP htdocs directory:

  cd C:\xampp\htdocs

- Then clone the repository:

  git clone https://github.com/Avocdont/Pet_Adoption.git

Step 3: Start Apache and MySQL
- Open the XAMPP Control Panel
- Click "Start" next to Apache
- Click "Start" next to MySQL

Step 4: Import the Database
- Go to http://localhost/phpmyadmin
- Click "Import"
- Click "Choose File" and select the file named `padpt.sql`
- Click "Go" to import

Step 5: Access the Website
- In your web browser, go to:

  http://localhost/pet_adoption_website_with_admin

- The website should now be running on your local machine


Admin Credentials

Default login:  
- Username: admin  
- Password: admin123  

Be sure to change the password after your first login for security reasons.



How to Operate the System:

Step 1: Homepage (index.php)
- Displays featured pets only (not all pets)
- Each featured pet includes an “Adopt” button

Step 2: Adoption Page (adopt.php)
- Shows all pets with the status “Available”
- Each pet has buttons to:
  - View more details
  - Adopt
- When "Adopt" is clicked, a form appears where the user enters:
  - Name
  - Contact information
  - Message
- When submitted, the adoption request is saved to the database

Step 3: Admin Login (admin_login.php)
- Admin logs in using their credentials
- Upon successful login, the admin is redirected to the dashboard

Step 4: Admin Dashboard (admin_dashboard.php)
- View and manage all submitted adoption requests
- Manage pet listings:
  - Add new pets
  - Edit existing pet info
  - Delete pets
  - Update pet availability status



Features:

- Homepage showing featured pets
- Full adoption page listing all available pets
- Pet details and adoption form
- Adoption request saved to the database
- Secure admin login
- Admin dashboard with pet and request management


License
-------
This project is open source and free to modify.
