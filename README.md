Project Overview:
This project creates a simple ATM login interface using Java Swing. The application allows users to enter their card number and PIN, and provides options to sign in, clear the fields, or sign up for a new account.

2. Components and Layout:
JFrame: The main window where all the components are placed.
JLabel: Used to display text and images on the frame. For example, labels for "Card No:", "Pin:", and the welcome message.
JTextField: A text field where users can enter their card number.
JPasswordField: A text field for entering the PIN, where input is masked.
JButton: Buttons for "Sign in", "Clear", and "Sign up".
ImageIcon and JLabel: Used to display an image logo on the interface.

3. Layout and Positioning:
The layout is set to null, meaning absolute positioning is used.
Components are placed at specific coordinates using setBounds().
The frame size is set to 800x447 pixels, and its position is set on the screen using setLocation().
4. Event Handling:
ActionListener: The Login class implements the ActionListener interface to handle button clicks.
Button Actions:
Sign In Button: (Currently not implemented) Intended to validate the entered card number and PIN against a database or predefined credentials.
Clear Button: Clears the text fields when clicked.
Sign Up Button: Opens a new sign-up form when clicked.
5. Process Flow:
User Interaction:
The user opens the application and is greeted with a welcome message and fields to enter their card number and PIN.
They can click the "Sign in" button to attempt to log in, the "Clear" button to reset the fields, or the "Sign up" button to open a new account registration form.
Event Handling:
When a button is clicked, the actionPerformed method is triggered. The source of the event is checked to determine which button was clicked, and the corresponding action is performed.
Sign-Up Process:
When the "Sign up" button is clicked, the current frame is hidden, and a new sign-up form is displayed.

![image](https://github.com/Sonamkandari/BankManagementproject/assets/145662567/930b1da7-4918-4952-8acc-59d4d5127645)


Labels: Used to display text descriptions for each input field (e.g., "Name", "Father's Name", "Date of Birth").
Text Fields: Input fields where users can type in their information (e.g., name, address, email).
Radio Buttons: Used for selecting options such as gender (Male, Female, Other) and marital status (Married, Unmarried). Only one option can be selected at a time within a group.
Date Chooser: A calendar component that allows users to select their date of birth.
Buttons: Includes a "Next" button that, when clicked, processes the entered information.
Random Application Number:

A random number is generated to uniquely identify each application form. This number is displayed at the top of the form.
Form Layout:

The form is laid out using absolute positioning, which places each component at a specific location within the window.
Event Handling:

An action listener is attached to the "Next" button. When the button is clicked, the listener gathers all the input data, performs validation checks, and attempts to save the data to a database.
Database Connection:

A separate class is used to handle the database connection. This class initializes a connection to a MySQL database using JDBC (Java Database Connectivity).
SQL queries are constructed to insert the collected form data into a database table.
Data Validation:

Basic validation checks are performed to ensure that required fields are not left empty (e.g., name field must be filled out).
Process Flow:
User Interaction:

The user opens the application and is presented with a form to fill in their personal details.
The user enters their information into text fields, selects options using radio buttons, and picks their date of birth from the date chooser.
Form Submission:

Once the user has filled out the form, they click the "Next" button.
The action listener associated with the button retrieves the entered data.
Data Validation:

The application checks that all required fields have been filled in.
If any required field is empty, an error message is displayed to the user.
Database Insertion:

If validation passes, the application prepares an SQL query to insert the data into a database.
The database connection class handles the execution of this query.
Feedback:

The user is informed whether the data has been successfully saved or if an error occurred during the process.

![image](https://github.com/Sonamkandari/BankManagementproject/assets/145662567/d4b5b5ee-c1bf-4093-b2c3-0e3575ccf24f)


now when in the signup page i entered the data it get saved in my data base which i have been made 


![image](https://github.com/Sonamkandari/BankManagementproject/assets/145662567/4b235d33-6b68-49ee-ad1f-def8d2611631)

