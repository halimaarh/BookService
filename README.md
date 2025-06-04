📘 Book Service
Base URL: https://bookservice-a2qm.onrender.com/api/v1/books

🔹 Get All Books
GET /books/

Description: Returns a list of all books.

🔹 Get Book by ID
GET /books/{bookId}

🔹 Delete Book by ID
DELETE /books/{bookId}

🔹 Create a Book
POST /books

Request Body:

json
Copy code
{
  "name": "Book Title",
  "weight": "0.45kg"
}
🔹 Update a Book
PUT /books/{bookId}

Request Body:

json
Copy code
{
  "name": "Updated Title",
  "weight": "0.50kg"
}
