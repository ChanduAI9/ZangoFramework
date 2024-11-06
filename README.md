# ZangoFramework



Book Management Project
A simple Django-based application for managing a library of books, with features for adding, updating, and managing book statuses.

Features
CRUD Operations: Create, Read, Update, and Delete books.
Status Management: Update book statuses (Available, Checked Out, Reserved, Damaged).
Admin Interface: Access Django’s admin panel for managing books and users


Endpoints

/book/all/ - (GET) List all books

/book/add/ - (POST) Add a new book

/book/<book_id>/edit/ - (GET, POST) Edit a book

/book/<book_id>/delete/ - (DELETE) Delete a book

/book/<book_id>/status/ - (POST) Update book status

/admin/ - (GET) Access admin panel
