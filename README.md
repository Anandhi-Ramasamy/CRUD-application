  OVERVIEW OF CRUD APPLICATION PROJECT

This project is a simple *CRUD (Create, Read, Update, Delete)* application built using *HTML, **CSS, and **JavaScript*. It demonstrates basic operations on data entries like adding, displaying, editing, and deleting records. Here's a breakdown of the components and functionalities:

 1. HTML Structure
   - *Form:* The user inputs a name and email in a form and submits it by clicking the "Add" button. The form is used to gather user data.
   - *Table:* Below the form is an empty table with three columns: "Name," "Email," and "Actions." Once the form is submitted, the table gets populated with the entered data.
   
   Key Elements:
   - Input fields: Name, Email and Password
   - Add button: To submit the form and add entries
   - Table headers: Name, Email, Password and Actions

 2. CSS for Styling
   - *Responsive and Clean Design:* The CSS ensures the form and table have a simple, user-friendly layout with proper spacing, alignment, and coloring.
   - *Buttons:* The buttons for editing and deleting data are styled with different colors for distinction:
     - Edit button: Orange
     - Delete button: Red

 3. JavaScript for Functionality
   - *Adding Data (Create):* When the user submits the form, the data is added to the table dynamically without refreshing the page. This is done using JavaScript's DOM manipulation.
   - *Displaying Data (Read):* Once added, the name and email are displayed in the table along with action buttons for editing or deleting the row.
   - *Editing Data (Update):* When the user clicks the "Edit" button on any table row, a prompt appears allowing the user to modify the existing data. The changes are reflected in the table.
   - *Deleting Data (Delete):* Clicking the "Delete" button removes the respective row from the table.

 Workflow
1. *User Inputs Data*: The user enters their name and email into the form and clicks "Add."
2. *Entry is Added to the Table*: The JavaScript function adds the new row to the table with "Edit" and "Delete" buttons.
3. *Edit or Delete Actions*: 
   - *Edit*: Allows the user to update the existing row.
   - *Delete*: Removes the row from the table.

 Practical Use
This CRUD project demonstrates core JavaScript skills and can be extended for real-world scenarios such as user management, task lists, or contact forms in web applications.
