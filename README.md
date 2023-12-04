# MERN Stack Blog Application

This project is a full-stack blog application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It features a backend that handles CRUD operations with a NoSQL database and a React frontend for user interaction. This application demonstrates basic CRUD operations in a full-stack environment.

## Features

- Create, read, update, and delete blog posts.
- Interactive frontend built with React and Bootstrap.

#### Installing

```bash
git clone https://github.com/AndriiSotnyk-leverx/blog-app
```

## Backend - MEN Stack Blog Application

### Getting Started

#### Prerequisites

- Node.js
- MongoDB
- npm (Node Package Manager)

```bash
cd blog-backend
npm install
```

#### Running the Server

```bash
npm start
```

The server will be running on `http://localhost:3000`.

#### Running Tests

```bash
npm test
```

### Configuration

Create a `.env` file in the root directory:

```plaintext
PORT=3001
MONGODB_URI=mongodb://localhost:27017/
API_VERSION=v1
```

## Frontend - React Blog Application

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Getting Started

#### Prerequisites

- Node.js v20.10.0
- npm (Node Package Manager)

#### Installation

```bash
cd blog-frontend
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Configuration

Create a `.env` file in the root directory:

```plaintext
REACT_APP_API_URL=http://localhost:3001/api/v1
```

## Built With

- [MongoDB](https://www.mongodb.com/) - The database used
- [Express.js](https://expressjs.com/) - The web framework used
- [React.js](https://reactjs.org/) - The frontend library used
- [Node.js](https://nodejs.org/) - The backend environment used
- [Bootstrap](https://getbootstrap.com/) - Frontend framework
