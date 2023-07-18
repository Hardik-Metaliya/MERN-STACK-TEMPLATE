# MERN Stack Template

This is a MERN (MongoDB, Express.js, React.js, Node.js) stack template that provides a starting point for building web applications using the MERN stack.

## Technology used

[![React](https://img.shields.io/badge/React-18.2.0-blue)](https://reactjs.org/)
[![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-1.9.5-purple)](https://redux-toolkit.js.org/)
[![React Router](https://img.shields.io/badge/React%20Router-6.14.2-orange)](https://reactrouter.com/)
[![Express.js](https://img.shields.io/badge/Express.js-4.18.2-green)](https://expressjs.com/)
[![Mongoose](https://img.shields.io/badge/Mongoose-7.3.4-yellow)](https://mongoosejs.com/)
[![bcryptjs](https://img.shields.io/badge/bcryptjs-2.4.3-blueviolet)](https://www.npmjs.com/package/bcryptjs)
[![cors](https://img.shields.io/badge/cors-2.8.5-blueviolet)](https://www.npmjs.com/package/cors)
[![dotenv](https://img.shields.io/badge/dotenv-16.3.1-yellowgreen)](https://www.npmjs.com/package/dotenv)
[![nodemon](https://img.shields.io/badge/nodemon-3.0.1-red)](https://www.npmjs.com/package/nodemon)

## Features

- Server-side rendering with React.js
- API endpoints using Express.js
- Database integration with MongoDB
- Frontend routing with React Router
- State management with Redux Toolkit
- Environment variable configuration with dotenv

## Prerequisites

Before getting started, make sure you have the following installed on your machine:

- Node.js (v14 or above)
- MongoDB

## Getting Started

To get a local copy of the project up and running, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Hardik-Metaliya/MERN-STACK-TEMPLATE
   ```

2. Install dependencies for both the server and client:
   ```bash
   cd server
   npm install
   ```
   ```bash
   cd ../client
   npm install
   ```
3. Set up environment variables:

   Create a `.env` file in the server directory.

4. Start the development server:

   ```bash
   # Start the server
   cd server
   npm run dev

   # Start the client
   cd ../client
   npm run dev
   ```

5. Open your browser and visit `http://localhost:3000` to see the application running.

6. Folder Structure

- client/

  - .eslintrc.cjs
  - .gitignore
  - index.html
  - package-lock.json
  - package.json
  - vite.config.js
  - public/
    - vite.svg
  - src/
    - App.css
    - App.jsx
    - index.css
    - main.jsx
    - assets/
      - react.svg
    - components/
      - navigation/
    - features/
    - pages/
    - services/
    - store/
    - utils/

- server/
  - index.js
  - package-lock.json
  - package.json
  - middleware/
  - model/
  - routes/

## Scripts

In the project, you can run the following scripts:

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the client for production.
- `npm run start`: Starts the production server.
- `npm run lint`: Lints the client-side code using ESLint.
- `npm run test`: Runs tests (if available).

## Git Commiting Standards

```
<type>(<scope>): <subject>

<body>

<footer>
```

### Writing Commit messages

<type>: Describes the type of the commit. Common types include:

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactorings
- `test`: Adding or modifying tests
- `chore`: Maintenance tasks, build configurations, etc.
- `created` :Added a file or folder
- `deleted` :Removed a file or folder
  <scope> (optional): Represents the scope or area of the codebase that is affected by the commit.

<subject>: A short, descriptive summary of the commit, written in the imperative mood.

<body> (optional): A more detailed description of the changes made in the commit. It can include multiple paragraphs if necessary.

<footer> (optional): Additional information such as references to issue numbers or other related commits.

### Example

```
feat(api): Add user authentication endpoint

- Added POST /api/auth endpoint for user authentication
- Implemented JWT-based authentication
- Stored user credentials securely using bcrypt

Closes #123
```
