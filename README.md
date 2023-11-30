# BookLibrary API

![Node.js](https://img.shields.io/badge/Node.js-14.17.0-green)
![Express.js](https://img.shields.io/badge/Express.js-4.17.1-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-4.4.4-orange)

A simple RESTful API for managing a BookLibrary, built with Node.js, Express.js, and MongoDB.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)

## Introduction

This project provides a basic API for managing books in a BookLibrary. It's built using Node.js for the server, Express.js for routing, and MongoDB for data storage.

## Features

- **Create:** Add new books to the database.
- **Read:** Retrieve information about all books or a specific book by ID.
- **Update:** Modify details of a book using its ID.
- **Delete:** Remove a book from the database by ID.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed (version 14.17.0 recommended).
- [MongoDB](https://www.mongodb.com/) installed and running.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/bookstore-api.git
   ```

# Navigate to the project directory:

- cd bookstore-api

# Install dependencies:

- npm install

# Set up your environment variables:

Create a .env file in the root of the project and add the following:

- PORT=3000
- MONGODB_URI=mongodb://localhost:27017/bookstore
  Adjust the PORT and MONGODB_URI values as needed.

# Run the application:

- npm run server
  The server will start at http://localhost:3000.

## Usage

The API provides endpoints for managing books. Use tools like Postman to interact with the API.

## API Endpoints

- POST /api/books: Create a new book.
- GET /api/books: Retrieve all books.
- GET /api/books/:id: Retrieve a specific book by ID.
- DELETE /api/books/:id: Delete a book by ID.
- PATCH /api/books/:id: Update a book by ID.
