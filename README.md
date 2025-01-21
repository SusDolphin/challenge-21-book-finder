# Book Finder Application

A MERN stack application that allows users to search for and save books using the Google Books API.

## Description

Book Finder is a full-stack web application built with MongoDB, Express.js, React, and Node.js. Users can search for books using the Google Books API, view book details, and save their favorite books to their personal collection.

## Features

- User authentication (signup/login)
- Book search functionality using Google Books API
- Save books to personal collection
- View saved books
- Remove books from saved collection
- Responsive design

## Technologies Used

### Frontend
- React
- Apollo Client
- GraphQL

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- GraphQL
- Apollo Server

## Installation

1. Clone the repository:
```bash
git clone https://github.com/SusDolphin/challenge-21-book-finder.git
```

2. Install dependencies for both client and server:
```bash
# Install root dependencies
npm install

# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
```

3. Create a `.env` file in the server directory and add your MongoDB URI and JWT secret:
```
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

4. Start the development server:
```bash
# From the root directory
npm run develop
```

## Usage

1. Create an account or log in
2. Search for books using the search bar
3. Click "Save" on any book you want to add to your collection
4. View your saved books in the "Saved Books" page
5. Remove books from your collection as needed

## Deployment

This application can be deployed using platforms like Heroku or Render. Make sure to:
- Set up your environment variables
- Configure your build settings
- Set the publish directory to `dist` for the client

https://challenge-21-book-finderpub.onrender.com

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
