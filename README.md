| HTTP verb | URL            | Request body | Action                               |
|-----------|----------------|--------------|--------------------------------------|
| POST      | /books         | JSON         | Add new book                         |
| GET       | /books         |              | Returns all the books                |
| GET       | /books/:bookId |              | Returns the specified book's details |
| PUT       | /books/:bookId | JSON         | Edits the specified book             |
| DELETE    | /books/:bookId |              | Deletes the specified book           |