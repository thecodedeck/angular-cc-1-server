# Node.js Server for Angular Storefront - Crash Course

This server provides the backend functionality for the Angular frontend, allowing users to perform CRUD (Create, Read, Update, Delete) operations on products. The server utilizes Express and interacts with a JSON file to manage product data.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Features

- **Express Server:** The server is built with Express, providing a robust and scalable backend.
- **CRUD Operations:** Supports Create, Read, Update, and Delete operations on product data.
- **JSON Data Storage:** Products are stored and manipulated within a JSON file instead of a traditional database.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/thecodedeck/angular-cc-1-server.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

1. Run the server:
   ```bash
   npm start
   ```
2. The server will be running on http://localhost:3000/.

3. The Angular frontend will interact with these API endpoints to perform CRUD operations on products.

## License

This project is licensed under the MIT License.
