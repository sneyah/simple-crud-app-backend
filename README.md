# Simple CRUD App Backend

This is a simple CRUD (Create, Read, Update, Delete) application backend built with Node.js, Express, and MongoDB. The application demonstrates basic CRUD operations on products and is containerized using Docker for easy deployment and scalability.

## Features

- Create a new product
- Retrieve all products
- Retrieve a single product by ID
- Update a product by ID
- Delete a product by ID

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) installed on your machine
- [MongoDB](https://www.mongodb.com/) Atlas or a local MongoDB instance
- [Docker](https://www.docker.com/) installed for containerization (optional)

### Installation

To install and set up the Simple CRUD App Backend, follow these steps:

1. Clone the repository:

    ```sh
    git clone https://github.com/sneyah/simple-crud-app.git
    cd simple-crud-app
    ```

2. Install dependencies:

    ```sh
    npm install
    ```

    This command will install all the necessary dependencies required for the application to run.

3. Run the application:

    ```sh
    npm start
    ```

    This command will start the server, and you should see a message indicating that the server is running on a specific port (e.g., `Server is running on port 3000`).

4. Access the application:

    Once the server is running, you can access the application's endpoints using tools like cURL, Postman, or any web browser. The base URL for the API endpoints will be `http://localhost:3000/api/products`.

