# cetm73_LibProject

# Library System

This is a simple library system implemented in Python with an SQLite database for backend storage and HTML, CSS, and JavaScript for the frontend user interface.

## Folder Structure

library_system/
│
├── backend/
│ ├── library_script.py # Python script for database implementation
│ ├── database.db # SQLite database file
│ └── init.py # Initialization file for the backend package
│
├── frontend/
│ ├── index.html # HTML file for the home page
│ ├── login.html # HTML file for the login page
│ ├── register.html # HTML file for the registration page
│ ├── borrow.html # HTML file for the borrow book page
│ ├── return.html # HTML file for the return book page
│ ├── admin.html # HTML file for the admin dashboard
│ ├── fine.html # HTML file for displaying fines
│ ├── styles.css # CSS stylesheet for styling
│ └── script.js # JavaScript file for client-side logic
│
├── static/ # Directory for static files (images, etc.)
│ └── images/ # Directory for images
│
└── README.md # README file with project information

markdown


## Features

- User authentication and authorization
- CRUD operations for books, admin, and library users
- Borrowing and returning books
- Fine penalties for late book returns
- Responsive and intuitive user interface

## Technologies Used

- Python
- SQLite
- HTML
- CSS
- JavaScript

## How to Run

1. Clone this repository to your local machine.
2. Navigate to the `backend` directory and run the `library_script.py` script to create the SQLite database.
3. Start a local server or open the `index.html` file in your browser to access the library system.

## Contributors

- Kareem Yusuff (https://github.com/kay1yus)
