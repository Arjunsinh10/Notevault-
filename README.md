# NoteVault

NoteVault is a web application developed using Java Server Pages (JSP) and JDBC API. It helps users to note down important notes, manage them efficiently, and perform CRUD (Create, Read, Update, Delete) operations on the notes. The application aims to provide a simple and user-friendly interface for managing personal or professional notes.

## Features

- **User Authentication**: Secure login and registration system to protect user data.
- **Create Notes**: Users can create new notes with a title and content.
- **Read Notes**: View all the notes or a specific note with detailed information.
- **Update Notes**: Edit the content and title of existing notes.
- **Delete Notes**: Remove notes that are no longer needed.
- **Search Functionality**: Quickly find notes by keywords.
- **User-Friendly Interface**: Clean and intuitive design for easy navigation and usage.

## Technologies Used

- **Java Server Pages (JSP)**: For building dynamic web pages.
- **JDBC API**: For database connectivity and operations.
- **Servlets**: For handling HTTP requests and responses.
- **MySQL**: As the relational database management system.
- **HTML/CSS**: For front-end structure and styling.
- **JavaScript**: For front-end interactivity and validations.
- **Bootstrap**: For responsive design.

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/notevault.git
et up the database:

2.**Install MySQL and create a database named notevault**.
Run the SQL script provided in the database directory to create the necessary tables.
Configure the application:

3.**Update the database configuration in the dbconfig.properties file located in the src directory with your MySQL credentials.
Deploy the application**:

Deploy the application on a web server like Apache Tomcat.

## Usage


**Register**: Create a new account by providing a username, password, and email.
**Login**: Access your account by logging in with your credentials.
**Create a Note**: Click on the 'New Note' button and fill in the title and content fields.
**View Notes**: View all your notes on the dashboard or search for specific notes using the search bar.
**Edit Notes**: Click on the 'Edit' button next to the note you want to update.
**Delete Notes**: Click on the 'Delete' button next to the note you want to remove.
