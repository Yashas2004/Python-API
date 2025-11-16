# Flask User API

A simple Flask-based REST API for managing user data.

## Features

- Get user information by ID
- Create new users

## Installation

1. Install dependencies:
   ```sh
   pip install flask
   ```

2. Run the application:
   ```sh
   python main.py
   ```

The API will run on `http://localhost:5000` in debug mode.

## API Endpoints

### GET /get-user/<user_id>
Retrieves user data for the given user ID. Optionally, add `?extra=value` to include extra data.

**Response:**
```json
{
  "user_id": "123",
  "name": "John Doe",
  "email": "john.doe@example.com",
  "extra": "value"  // if provided
}
```

### POST /create-user
Creates a new user with the provided JSON data.

**Request Body:**
```json
{
  "name": "Jane Doe",
  "email": "jane.doe@example.com"
}
```

**Response:**
Returns the same data with a 201 status code.
```// filepath: README.md
# Flask User API

A simple Flask-based REST API for managing user data.

## Features

- Get user information by ID
- Create new users

## Installation

1. Install dependencies:
   ```sh
   pip install flask
   ```

2. Run the application:
   ```sh
   python main.py
   ```

The API will run on `http://localhost:5000` in debug mode.

## API Endpoints

### GET /get-user/<user_id>
Retrieves user data for the given user ID. Optionally, add `?extra=value` to include extra data.

**Response:**
```json
{
  "user_id": "123",
  "name": "John Doe",
  "email": "john.doe@example.com",
  "extra": "value"  // if provided
}
```

### POST /create-user
Creates a new user with the provided JSON data.

**Request Body:**
```json
{
  "name": "Jane Doe",
  "email": "jane.doe@example.com"
}
```

**Response:**
Returns the same data with a 201 status code.
