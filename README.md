# Node.js Blog Application

## Description

This is a blog application built using Node.js, providing features such as user authentication, post creation, and management. It supports a dynamic interface with routing and basic CRUD operations.

## Features

- User Authentication (Login, Register)
- Create, Read, Update, Delete (CRUD) for blog posts
- Responsive design for better usability
- Template-driven rendering using a popular templating engine (e.g., EJS, Pug)

## Installation

1. Clone this repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd NodeJs-Blog
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up environment variables:

   - Create a `.env` file in the root directory.
   - Add the following keys:
     ```env
     PORT=3000
     DATABASE_URL=your-database-url
     SECRET_KEY=your-secret-key
     ```

5. Run the application:

   ```bash
   npm start
   ```

6. Open the application in your browser at [http://localhost:3000](http://localhost:3000).

## Project Structure

```
NodeJs-Blog/
│
├── public/         # Static files (CSS, JS, images)
├── views/          # Template files
├── routes/         # Application routes
├── controllers/    # Business logic for routes
├── models/         # Database models
├── .env.example    # Example environment file
├── package.json    # Project metadata and dependencies
├── server.js       # Entry point of the application
└── README.md       # Project documentation
```

This JSON snippet appears to be from the `package.json` file of a Node.js project, which defines the project's metadata, scripts, dependencies, and dev dependencies. Here's a breakdown:

---

### **Dependencies**
Dependencies are external packages your application needs to run. Here are the ones listed:

1. **`bcrypt`**: Used for hashing passwords securely.
2. **`connect-mongo`**: A MongoDB session store for `express-session`, useful for persisting session data in MongoDB.
3. **`cookie-parser`**: Middleware for parsing cookies attached to client requests.
4. **`dotenv`**: Loads environment variables from a `.env` file into `process.env`, making sensitive information like API keys manageable.
5. **`ejs`**: Embedded JavaScript templating engine for rendering HTML with dynamic data.
6. **`express`**: A web framework for building server-side applications.
7. **`express-ejs-layouts`**: A layout manager for EJS, simplifying the use of layouts in views.
8. **`express-session`**: Middleware for managing user sessions.
9. **`jsonwebtoken`**: Used to create and verify JSON Web Tokens (JWTs) for authentication and authorization.
10. **`method-override`**: Allows using HTTP verbs like PUT or DELETE in places where the client doesn't support them.
11. **`mongoose`**: A MongoDB object modeling tool for Node.js, providing schema-based solutions for data modeling.

---

### **Dev Dependencies**
Dev dependencies are packages needed only during development:

1. **`nodemon`**: Monitors changes in your files and restarts the server automatically, useful for a better development workflow.

---

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).



