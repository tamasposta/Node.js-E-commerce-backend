# Node.js E-commerce Backend

![Node.js](https://img.shields.io/badge/Backend-Node.js-green.svg)
![Prettier](https://img.shields.io/badge/Code%20Formatter-Prettier-orange.svg)
![Mongoose](https://img.shields.io/badge/Database-Mongoose-blue.svg)
![Bcrypt](https://img.shields.io/badge/Security-Bcrypt-yellow.svg)
![Express](https://img.shields.io/badge/Framework-Express-red.svg)
![Cors](https://img.shields.io/badge/Security-Cors-blue.svg)
![Dotenv](https://img.shields.io/badge/Configuration-Dotenv-brightgreen.svg)
![Jsonwebtoken](https://img.shields.io/badge/Authentication-Jsonwebtoken-black.svg)
![Multer](https://img.shields.io/badge/File%20Upload-Multer-lightgrey.svg)
![Nodemon](https://img.shields.io/badge/Development-Nodemon-lightblue.svg)
![Morgan](https://img.shields.io/badge/Logging-Morgan-lightgreen.svg)

## Description

Node.js E-commerce Backend is a robust backend application for e-commerce platforms built using Node.js. This project was developed to practice and deepen my understanding of Node.js, along with utilizing various libraries such as Express, Mongoose, Bcrypt, Cors, Dotenv, Jsonwebtoken, Multer, Nodemon, and Morgan.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/nodejs-ecommerce-backend.git
   ```
2. Navigate to the project directory
   ```bash
   cd nodejs-ecommerce-backend
   ```
3. Install the dependencies
   ```bash
   npm install
   ```

## Usage

1. Create a `.env` file in the root directory and add the necessary environment variables:
   ```plaintext
   MONGO_URI=your_mongo_uri
   JWT_SECRET=your_jwt_secret
   ```
2. Start the development server
   ```bash
   npm run dev
   ```

## Features

- User authentication and authorization
- Product management
- Order management
- File upload for product images
- Secure API with JWT
- Logging and monitoring

## Technologies Used

- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine
- **Prettier**: Code formatter
- **Mongoose**: Elegant MongoDB object modeling for Node.js
- **Bcrypt**: Password hashing function
- **Express**: Fast, unopinionated, minimalist web framework for Node.js
- **Cors**: Node.js CORS middleware
- **Dotenv**: Zero-dependency module that loads environment variables from a .env file into process.env
- **Jsonwebtoken**: Implementation of JSON Web Tokens
- **Multer**: Middleware for handling `multipart/form-data`, used for uploading files
- **Nodemon**: Simple monitor script for use during development of a Node.js app
- **Morgan**: HTTP request logger middleware for Node.js

## Contributing

Contributions are welcome! Please fork this repository and create a pull request with your changes.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a pull request

## Acknowledgements

- [Node.js](https://nodejs.org/) for providing the runtime
- [Prettier](https://prettier.io/) for code formatting
- [Mongoose](https://mongoosejs.com/) for MongoDB object modeling
- [Bcrypt](https://www.npmjs.com/package/bcrypt) for password hashing
- [Express](https://expressjs.com/) for the web framework
- [Cors](https://www.npmjs.com/package/cors) for enabling CORS
- [Dotenv](https://www.npmjs.com/package/dotenv) for managing environment variables
- [Jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) for JWT implementation
- [Multer](https://www.npmjs.com/package/multer) for handling file uploads
- [Nodemon](https://nodemon.io/) for development monitoring
- [Morgan](https://www.npmjs.com/package/morgan) for logging
