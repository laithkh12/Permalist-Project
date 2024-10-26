# Permalist

Permalist is a simple task management web application built with Express.js and PostgreSQL. It allows users to manage their to-do items by adding, editing, and deleting tasks. The application connects to a PostgreSQL database to store tasks persistently.

## Features

- View a list of tasks.
- Add new tasks.
- Edit existing tasks.
- Delete tasks.
- Data is stored in a PostgreSQL database.

## Prerequisites

- Node.js (>= 14.x)
- PostgreSQL
- npm (Node Package Manager)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/permalist.git
   cd permalist
   ```
1. **Install dependencies:
   ```bash
   npm install
   ```
2. **Create a .env file in the root directory of your project with the following content:
   ```bash
   DB_PASSWORD=your_database_password
   ```
 - Replace your_database_password with the password for your PostgreSQL database.
   
3. **Set up the PostgreSQL database:
   ```bash
   CREATE TABLE items (
    id SERIAL PRIMARY KEY,
    title VARCHAR(255) NOT NULL
    );
   ```
4. **Run the application:
   ```bash
   npm start
   ```

## Usage
- Navigate to the home page (/) to view your tasks.
- Use the input field to add new tasks.
- Click on the edit button to change an existing task.
- Click on the delete button to remove a task.

## Contributing
- Contributions are welcome! Please feel free to submit a pull request or open an issue.

## Acknowledgements
- Express.js - Fast, unopinionated, minimalist web framework for Node.js.
- PostgreSQL - Powerful, open source object-relational database system.


### Notes
- Be sure to replace `your-username` in the clone command with your actual GitHub username.
- Adjust the database creation SQL as necessary for your specific requirements.
- Include any other relevant information or acknowledgments as needed.



   
