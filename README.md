# E-commerce Back End

This is the back end for an e-commerce website built using Express.js and Sequelize. It allows managers at an internet retail company to manage categories, products, and tags in their database.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Walkthrough Video](#walkthrough-video)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Description

The E-commerce Back End provides a RESTful API for managing categories, products, and tags. It uses Express.js as the web framework and Sequelize as the ORM to interact with a MySQL database. By following the provided user story and acceptance criteria, you'll be able to set up the database, seed it with test data, and interact with the API endpoints using tools like Insomnia Core.

## Installation

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Install dependencies using the following command:

npm install


4. Set up your MySQL database and configure the environment variables. Create a `.env` file in the root directory of the project and add the following:

DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password


5. Use the `schema.sql` file in the `db` folder to create your database using MySQL shell commands.

6. Seed your database by running the following command:

npm run seed


## Usage

To start the server and sync Sequelize models to the MySQL database, run the following command:

npm start


Once the server is running, you can use a tool like Insomnia Core to test the API endpoints. The routes for categories, products, and tags are available for performing CRUD operations.

## Walkthrough Video

[Link to Walkthrough Video](#) - (Replace this with the link to your walkthrough video)

Watch this video to see how to set up the database, seed it with test data, start the server, and test the API endpoints using Insomnia Core.

## Testing

This project uses Jest for unit testing. To run the tests, use the following command:

npm test


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
