# Login and Register Module Using JWT and MongoDB with ReactJS

This project is a simple implementation of a login and registration module using JSON Web Tokens (JWT) for authentication and MongoDB for data storage. It's built with ReactJS on the front end and utilizes Node.js and Express.js on the backend.

## Features

- User registration with validation
- User login with JWT authentication
- Secure password hashing using bcrypt
- MongoDB integration for data storage
- Protected routes for authenticated users

## Prerequisites

Before running this project locally, make sure you have the following installed:

- Node.js and npm (Node Package Manager)
- MongoDB

## Installation

1. Clone the repository:

```bash
git clone https://github.com/ibshaikh/login-register.git
```

2. Navigate to the project directory:

```bash
cd registerlogin
```

3. Install dependencies for both the server and client:

```bash
cd registerlogin
npm install
cd ../client
npm install
```

## Configuration

1. MongoDB Configuration:

   - Make sure MongoDB is running on your local machine or provide the appropriate connection URI in `.env` file.

2. JWT Secret Key:

   - Generate a secret key and replace the placeholder in `.env` with your secret key.

## Usage

1. Start the server:

```bash
cd registerlogin
node app.js
```

2. Start the client:

```bash
cd registerlogin
cd client
npm run dev
```

3. Visit `http://localhost:3000` in your browser to access the application.

## Endpoints

- `/api/register`: POST request to register a new user.
- `/api/login`: POST request to authenticate and login a user.

## Contributing

Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

**Developer Name:** Ibram Shaikh  
**LinkedIn:** [Ibram Shaikh](https://www.linkedin.com/in/ibram-shaikh-5a3881191/)
