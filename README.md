# MelodyStream

A backend music streaming platform built with **Node.js, Express.js, MongoDB, and Mongoose**.

### Features
- JWT-based authentication and authorization
- Music and album management
- Secure password hashing with bcrypt
- Media uploads using Multer and ImageKit
- RESTful API architecture
- MongoDB database integration

### Tech Stack
**Node.js · Express.js · MongoDB · Mongoose · JWT · bcrypt · Multer · ImageKit**

### Setup

```bash
npm install
npm run dev
```

Configure the required environment variables in `.env` before running the application.



### Project Structure

```text
MelodyStream/
├── controllers/       # Request handling and business logic
├── models/            # Mongoose schemas
├── routes/            # API routes
├── middleware/        # Authentication and request middleware
├── services/          # External services such as ImageKit
├── utils/             # Utility functions
├── uploads/           # Temporary uploaded files
├── server.js          # Application entry point
├── package.json
└── .env               # Environment configuration
