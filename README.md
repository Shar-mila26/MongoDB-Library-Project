# MongoDB Library Management System



## Project Overview

This project demonstrates a \*\*Library Book Management System\*\* using \*\*MongoDB\*\*.  

It covers \*\*CRUD operations\*\*, schema design, conditions, and basic error handling using `mongosh`.



---



## Technologies Used

- MongoDB

- mongosh

- Windows Command Prompt



---



## Database Details

- **Database Name:** libraryDB

- **Collection Name:** books



---



## Book Schema

Each book document contains:

- `title` (String)

- `author` (String)

- `category` (String)

- `publishedYear` (Number)

- `availableCopies` (Number)



---



## CRUD Operations Performed



### Insert Books

Inserted multiple book records into the `books` collection.



### Read Books

- Read all books

- Find books by category

- Find books published after a specific year



### Update Books

- Updated available copies

- Prevented negative stock updates



### Delete Books

- Deleted a book when `availableCopies` reached `0`

- Verified deletion using `find()`



---



## Error Handling

- Prevented invalid updates

- Handled book not found scenarios

- Ensured no negative stock values



---


## Sample Commands Used

```js

db.books.find()

db.books.updateOne()

db.books.deleteOne()

Project verified with CRUD operations and error handling.




