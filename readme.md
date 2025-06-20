# Item Manager

Item Manager is a simple, full-stack application designed to help you efficiently manage and organize items. Built with a Node.js/Express backend, an SQLite database, and a React frontend, this project provides a straightforward solution for adding, viewing, editing, and deleting items. Whether you’re managing inventory, personal collections, or task lists, Item Manager offers a clean and flexible foundation.

## Features

- Add, view, edit, and delete items
- RESTful API with complete CRUD operations
- SQLite database integration for persistent storage
- React-based frontend for easy interaction
- Full API documentation

## Getting Started

### Prerequisites

- Node.js and npm installed
- (Optional) Yarn for dependency management

### Backend Setup

1. Navigate to the `backend` folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the backend server:
   ```bash
   npm start
   ```
   The backend will run at [http://localhost:5001](http://localhost:5001).

### Frontend Setup

1. Open a new terminal and navigate to the `frontend` folder:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the React app:
   ```bash
   npm start
   ```
   The frontend will run at [http://localhost:3000](http://localhost:3000).

## API Documentation

For detailed information about available endpoints, request/response formats, and example usage, please see the [API Documentation](./api_documentation.md).

## Testing

You can test the Item Manager by:

- Using the React frontend to add, edit, and delete items
- Sending requests directly to the API using tools like `curl` or Postman (see [API Documentation](./api_documentation.md) for examples)

## License

This project is open source. See the LICENSE file for details.

---
