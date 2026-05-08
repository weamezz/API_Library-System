# API_Library-System
API Testing Project using Postman for Library System (Add, Get, Delete Books) with automated test scripts and validations.

#  Library API Testing Project

# Project Overview

This project contains automated API testing for a Library system using Postman.
It validates core functionalities such as adding a book, retrieving book details, and deleting a book.

---

# Features Tested

* Add Book API
* Get Book by ID API
* Delete Book API

---

# Tools Used

* Postman
* Newman (for CLI execution)
* JavaScript (for test scripts)

---

# Test Scenarios

Add Book

* Validate status code = 200
* Validate response contains `Msg` and `ID`
* Validate content-type
* Validate response time
* Validate success message
* Validate generated book ID logic

---

Get Book by ID

* Validate status code = 200
* Validate returned book البيانات
* Schema validation

---

Delete Book

* Validate status code
* Validate response time
* Handle cleanup scenarios

---

Dynamic Data Handling

* Random ISBN generation
* Using collection variables
* Data driven باستخدام iteration data

---

Project Structure

```
Library-API-Testing/
 ├── collection.json
 └── README.md
```

---

Key Highlights

* Automated test scripts
* End-to-end flow (Add → Get → Delete)
* Error handling & cleanup logic
* Schema validation

---



