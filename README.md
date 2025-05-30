📚 Book Service API
Base URL: https://bookservice-a2qm.onrender.com/api/v1/books

📘 Get All Books
Method: GET

Endpoint: /books

Description: Retrieves a list of all books.

🔍 Get Book by ID
Method: GET

Endpoint: /books/{id}

Description: Retrieves a book by its unique ID.

❌ Delete Book by ID
Method: DELETE

Endpoint: /books/{id}

Description: Deletes a book by its ID.

➕ Create a New Book
Method: POST

Endpoint: /books

Body (JSON):

json
Copy code
{
  "name": "Book Title",
  "weight": "0.45kg"
}
✏️ Update Book by ID
Method: PUT

Endpoint: /books/{id}

Body (JSON):

json
Copy code
{
  "name": "Updated Book Title",
  "weight": "0.50kg"
}
