# GraphQL-React-App

A full-stack web application built with **Node.js (Express)** and **React**, integrated with **GraphQL** for efficient data querying and manipulation. This project demonstrates features such as CRUD operations, user authentication and authorization, frontend and backend validation, **MongoDB** integration, image uploads, and dynamic UI rendering.

## Features

- **CRUD Operations**: Create, Read, Update, and Delete posts and user data.
- **GraphQL API**: Flexible and efficient data querying and manipulation.
- **Authentication & Authorization**: Secure login and user access control.
- **Validation**:
  - Backend validation with `graphql` schema.
  - Frontend form validation.
- **MongoDB**: A NoSQL database for data storage.
- **Image Upload**: Upload and manage images.
- **Dynamic UI Rendering**: Interactive and responsive frontend design.

## Project Structure

```
graphql-react-app/
├── client/       # React frontend
├── server/       # Node.js backend
```

## Installation

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [MongoDB](https://www.mongodb.com/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/uthpalasam7/graphql-react-app.git
   cd graphql-react-app
   ```

2. Install dependencies for both client and server:
   ```bash
   cd server
   npm install
   cd ../client
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the `server/` directory and add your MongoDB connection URL:
     ```env
     MONGODB_URI=your-mongodb-connection-string
     ```

4. Start the development server:
   - Start the backend:
     ```bash
     cd server
     npm start
     ```
   - Start the frontend:
     ```bash
     cd client
     npm start
     ```

5. Access the app:
   Open your browser and navigate to `http://localhost:3000`.


## Contribution

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
