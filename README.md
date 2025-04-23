# 📚 Book Management API

A RESTful API built with **Express.js** and **MongoDB** to manage a library's book inventory. This project includes full CRUD operations, using **Mongoose** as the ODM and **Postman** for testing.

---

## 🚀 Features

- Add new books to the database
- Retrieve all books or a specific book by ID
- Update existing book details
- Delete books from the database

---

## 🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose 
- Nodemon
- Postman (for API testing)

---

## 📁 Project Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/book-management-api.git
   cd book-management-api

#  Install dependencies
npm install

#  Start the server
nodemon .\index.js




❗️ Error Handling
All routes handle common errors like:

Invalid MongoDB ObjectIDs

Missing required fields

Non-existent resources

Responses follow the format:

json
Copy code
{
  "error": "Description of the error"
}



🧪 Testing
Use the provided Postman collection to test:

*All CRUD operations
*Edge cases and validations



📚 References
 *Mongoose Documentation
 *Express Routing
 *MongoDB Atlas Setup
