# codsoft_taskno-5
# Contact Management System

The Contact Management System is a Python application that allows users to manage their contacts effectively. It provides features such as adding new contacts, viewing existing contacts, searching for contacts, updating contact information, and deleting contacts.

## Functionality

### 1. Add New Contact
- Users can add a new contact by providing details such as store name, phone number, email, and address.
- Input validation ensures that valid information is entered for each field.
- Contact details are saved to a text file for future reference.

### 2. View Contacts
- Users can view all existing contacts stored in the system.
- Contact details are displayed in a structured format, including store name, phone number, email, and address.

### 3. Search Contacts
- Users can search for specific contacts by entering the name or phone number of the contact they want to find.
- The system retrieves and displays matching contacts based on the search query.

### 4. Delete Contact
- Users can delete a contact by specifying the name of the contact they want to remove.
- The system removes the contact from the list of stored contacts.

### 5. Update Contact
- Users can update the information of an existing contact by providing the name of the contact they want to update, the field they want to modify, and the new value for the field.
- The system updates the contact's information accordingly.

### 6. Exit
- Users can exit the application at any time by choosing the exit option.

## Libraries Used

- **re**: Python's built-in module for working with regular expressions. It is used for validating email addresses.
- **time**: Python's standard library module for time-related functions. It is used for adding delays and waiting for user input.
- **os**: Python's built-in module for interacting with the operating system. It is used for clearing the console screen and accessing files.
- **clear**: This command clears the console screen to improve readability and user experience.

## How to Run

1. Ensure you have Python installed on your system.
2. Run the following command in your terminal to execute the contact book application:

```bash
python contact_management_system.py
```

3. Follow the instructions displayed in the console to perform various contact management operations.

## Developer

- Developed by: wajihaadnan
