# go-library-api

<p align="center">
    <h1 align="center">GO-LIBRARY-API</h1>
</p>
<p align="center">
    <em><code>❯ About
A simple book management API built using Go and the Gin framework. </code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/blyoue/go-library-api?style=flat&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/blyoue/go-library-api?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/blyoue/go-library-api?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/blyoue/go-library-api?style=flat&color=0080ff" alt="repo-language-count">
</p>
<p align="center">
		<em>Built with the tools and technologies:</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Go-00ADD8.svg?style=flat&logo=Go&logoColor=white" alt="Go">
</p>

<br>

##  Overview

<code>❯ A simple book management API built using Go and the Gin framework. It supports adding, viewing, checking out, and returning books with basic error handling and CRUD operations. </code>

---

## Features

- ❯ Retrieve all books: View a list of all available books in the library.
- ❯ Retrieve a book by ID: Search for a specific book by its ID.
- ❯ Add a new book: Add a new book to the library collection by sending a POST request.
- ❯ Checkout a book: Borrow a book by decreasing the available quantity.
- ❯ Return a book: Return a borrowed book by increasing the available quantity.
- ❯ Error handling: Basic error handling for invalid book IDs and unavailable books.


##  Repository Structure

```sh
└── go-library-api/
    ├── README.md
    ├── go.mod
    ├── go.sum
    └── main.go
```

---

##  Modules

| File | Summary |
| --- | --- |
| [go.sum](https://github.com/blyoue/go-library-api/blob/main/go.sum) | <code>❯ Contains the cryptographic checksums for the dependencies used in the project.</code> |
| [go.mod](https://github.com/blyoue/go-library-api/blob/main/go.mod) | <code>❯ Defines the module's properties, including its dependencies and Go version.</code> |
| [main.go](https://github.com/blyoue/go-library-api/blob/main/main.go) | <code>❯ The main entry point of the application, where the API routes and handlers are defined.</code> |

---
