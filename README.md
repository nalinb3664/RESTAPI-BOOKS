# RESTAPI-BOOKS
Create a REST API to Manage a List of Books Using Node.js and Express.Build simple REST API endpoints for CRUD operations on books (no database needed, store in memory)

## 🚀 Features
- GET `/books` → Get all books
- POST `/books` → Add a new book
- PUT `/books/:id` → Update a book by ID
- DELETE `/books/:id` → Delete a book by ID

---

## 🛠 Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/books-api.git
   cd books-api
Install dependencies:

bash
Copy code
npm install
Start the server:

bash
Copy code
npm start
or run in dev mode with hot reload:

bash
Copy code
npm run dev
📌 Example Requests
GET all books
http
Copy code
GET http://localhost:3000/books
POST a new book
http
Copy code
POST http://localhost:3000/books
Content-Type: application/json

{
  "title": "Atomic Habits",
  "author": "James Clear"
}
PUT update a book
http
Copy code
PUT http://localhost:3000/books/1
Content-Type: application/json

{
  "title": "The Alchemist (Updated)"
}
DELETE a book
http
Copy code
DELETE http://localhost:3000/books/2
🧪 Testing
Use Postman or curl to test endpoints.

📜 License
MIT License

yaml
Copy code

---

# ✅ Next Steps
1. Run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Books REST API"
   git branch -M main
   git remote add origin https://github.com/<your-username>/books-api.git
   git push -u origin main
