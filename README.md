 Flask Blog Application with SQLAlchemy

This Flask-based blog application utilizes SQLAlchemy to interact with a relational database.
It incorporates various features for creating, editing, and managing blog posts, user registration, authentication, and authorization.

Key Features:

User Registration and Authentication: Users can register for an account using a secure form that hashes passwords before storing them in the database.
Flask-Login manages user sessions, allowing registered users to log in securely.

Authorization: Admin privileges are implemented using a decorator (admin_only), restricting access to certain functionalities such as creating, editing, and deleting posts. 
Only users with admin privileges can perform these actions.

Blog Post Management: Registered users can create, edit, and delete blog posts. 
Each post includes a title, subtitle, body text, author information, publication date, and optional image URL.

Commenting System: Users can leave comments on blog posts. Comments are associated with specific posts and include the commenter's information and the comment text.

Database Integration with SQLAlchemy: The application uses SQLAlchemy, a powerful ORM (Object-Relational Mapping) tool, to interact with a relational database. 
It defines database models for users, blog posts, and comments, establishing relationships between them.

Form Validation and Error Handling: Form validation is implemented to ensure that user inputs are sanitized and validated before processing. 
Flash messages provide feedback to users about the outcome of their actions, enhancing user experience and guiding them through the application's functionality.

Security Measures: Passwords are securely hashed using the PBKDF2 algorithm, and CSRF protection is enabled to prevent unauthorized requests. 
These measures protect user data and enhance application security.
How to Run:

Install the necessary Python packages listed in the requirements.txt file.
Run the Flask application using the command python app.py.
Access the application in your web browser at http://127.0.0.1:8002/.

![6A1B6D93-6F47-401B-9C8B-BA6E41BA9DB1_1_201_a](https://github.com/gabrielsorin88/Blog-with-Authentication-RealtionalDB-/assets/126314730/714e9f4a-8ed6-4227-aae1-2560eae3c6b0)
![8F9BC4A1-699D-4452-879E-DC25B9F2968B_1_201_a](https://github.com/gabrielsorin88/Blog-with-Authentication-RealtionalDB-/assets/126314730/fdc7266b-0ec9-42c4-802a-1fa819a23cb2)
![17100E54-8AA6-4299-9D09-B2809F65D64B_1_201_a](https://github.com/gabrielsorin88/Blog-with-Authentication-RealtionalDB-/assets/126314730/32d43da9-82a5-46d6-8d8e-f28dc5db7e98)
