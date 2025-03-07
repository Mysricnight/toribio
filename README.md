Step-by-Step Guide for Setting Up Django Project
1. Check Installed Django and Virtual Environment
Use the command line to check if Django and pip are installed on your system.

2. Set Up a Virtual Environment
Create and activate a virtual environment for the Django project.

3. Configure the Database
Create a new MySQL database named "student_management."
Update the settings file to include MySQL as the database engine.
Ensure the database name, username, password, host, and port are correctly set.

4. Define the Student Model
Create a model for student records with fields for Student ID, First Name, Last Name, Email, Date of Birth, Course, and Enrollment Date.
Set Student ID as the primary key and ensure Email is unique.

5. Apply Migrations
Generate and apply database migrations to create the necessary tables.

6. Implement CRUD Functionality
Set up the views file to handle Create, Read, Update, and Delete operations.
Ensure the models file defines how student data is structured.
Create a forms file to validate user input and handle form styling.
Define URL routing to connect views with templates.

7. Set Up Templates and Styling
Create a templates folder inside the students app.
Within the templates folder, create another folder named students.
Develop HTML files for displaying student data and managing CRUD operations.
Apply CSS styling directly in the HTML files.

8. Run the Django Project
Navigate to the project directory using the command line.
Run the Django development server to start the application.

9. Open and Test the Application
Access the running application in a web browser.
Test creating, editing, and deleting student records.
