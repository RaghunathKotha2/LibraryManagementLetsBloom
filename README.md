This is a Node.js project that implements a library management system using MongoDB, Express, and Mongoose. It allows users to perform CRUD operations on books in the library database.

## Features

- Fetch all books from the database
- Add a new book to the database
- Update an existing book in the database
- Delete a book from the database
- Handle errors and validations

## Installation

To run this project, you will need Node.js and MongoDB installed on your machine.

- Clone this repository from github link provided
- Navigate to the project directory
- Install the dependencies using `npm install`
- Start the MongoDB service using `mongod`
- Seed the database with some sample data
- Start the server using `npm start`

## Usage

You can use any API testing tool, such as Postman or Insomnia, to interact with the endpoints of this project. Alternatively, you can use `curl` commands in your terminal.

The available endpoints are:

- `GET /api/books` - Fetch all books from the database
- `POST /api/books` - Add a new book to the database
- `PUT /api/books/:id` - Update an existing book in the database
- `DELETE /api/books/:id` - Delete a book from the database
- 
The response body for fetching, adding, or updating a book will have the following fields:

- `_id` - The unique identifier of the book (string)
- `title` - The title of the book (string)
- `author` - The author of the book (string)
- `category` - The category of the book (string)
- `publish_date` - The publish date of the book (string)
- `copies_available` - The number of copies available in the library (number)
- `copies_total` - The total number of copies of the book (number)

