# Server-Side Application for Online Book Reviews

This application facilitates users in managing books, writing reviews, and engaging with book-related content. It utilizes MySQL as the database and leverages Sequelize.js as the ORM (Object-Relational Mapping) tool.

## Overview

The Server-Side Application for Online Book Reviews offers a RESTful API for handling user accounts, books, and reviews. Users can register, log in securely, and publish reviews for books they've read. Book management includes adding, updating, and deleting entries. Similarly, reviews can be created, modified, and removed. The goal is to provide a streamlined platform for book enthusiasts to share their insights and opinions effortlessly.

## Getting Started

Follow these steps to set up and run the application:

### Prerequisites

1. **Node.js**: Ensure Node.js is installed on your system. Download it from [nodejs.org](https://nodejs.org/).

2. **MySQL**: You'll need a MySQL database server installed and operational. Download MySQL from [mysql.com](https://www.mysql.com/).

### Installation

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the project directory**:

   ```bash
   cd <project-folder>
   ```

3. **Install dependencies**:

   ```bash
   npm install
   ```

4. **Configure the database connection**:
   
   - Create a MySQL database dedicated to this application.
   - Set up your MySQL database credentials and other necessary environment variables in the `.env` file.

5. **Start the application**:

   ```bash
   npm start
   ```

## API Documentation

Refer to the [API Documentation](https://documenter.getpostman.com/view/28416524/2s9YBxacHG) for detailed information and examples on how to use the API endpoints.

## Features

- **User Management**: Register, log in securely, and manage user accounts.
- **Book Management**: Add, update, delete, and list books effortlessly.
- **Review Management**: Write, edit, delete, and read book reviews seamlessly.

## Technologies Utilized

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web application framework for Node.js, simplifying API development.
- **MySQL**: Robust relational database management system.
- **Sequelize.js**: A powerful Node.js ORM for MySQL, leveraging promises for enhanced efficiency and clarity.
