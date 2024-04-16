# Files Manager

## Table of Contents

- [Description](#description)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Credits](#credits)
- [License](#license)

## Description

This project is a simple platform to upload and view files, built as a learning exercise. It includes user authentication via token, listing all files, uploading new files, changing file permissions, viewing files, and generating thumbnails for images.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Redis
- JavaScript (ES6)
- NoSQL
- Kue

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/alx-files_manager.git
```

2. Navigate to the project directory:

```bash
cd alx-files_manager
```

3. Install dependencies:

```bash
npm install
```

## Usage

1. Start the server:

```bash
npm start
```

2. Access the API endpoints using tools like cURL or Postman.

## Endpoints

- `GET /status`: Check if Redis and MongoDB are alive.
- `GET /stats`: Get the number of users and files in the database.
- `POST /users`: Create a new user.
- `GET /connect`: Sign in a user and generate an authentication token.
- `GET /disconnect`: Sign out a user and delete the authentication token.
- `GET /users/me`: Get the details of the authenticated user.
- `POST /files`: Upload a new file.
- `GET /files/:id`: Get details of a specific file.
- `GET /files`: Get all files for a specific parent ID with pagination.
- `PUT /files/:id/publish`: Publish a file.
- `PUT /files/:id/unpublish`: Unpublish a file.
- `GET /files/:id/data`: Get the content of a file.

## Credits

### Author

- Name: Ginika Elizabeth Nna.
- Email: elizabethginika9@gmail.com.

- Name: Goodness James Akoma.
- Email: (add email).

### Acknowledgements

- Special thanks to our team for their valuable contributions.
- Thanks to ALX for their guidance and support.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT)
