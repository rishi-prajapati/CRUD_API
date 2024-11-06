# Movie API

This is a simple API to manage movies using Go. You can perform basic operations like creating, reading, updating, and deleting movies.

## Endpoints

- **GET /movies**: Get all movies
- **GET /movies/{id}**: Get a movie by ID
- **POST /movies**: Create a new movie
- **PUT /movies/{id}**: Update a movie by ID
- **DELETE /movies/{id}**: Delete a movie by ID

## Run
1. Clone the repo: `git clone https://github.com/rishi-prajapati/CRUD-API.git`
2. Install dependencies: `go get github.com/gorilla/mux`
3. Run: `go run main.go`
4. API at `http://localhost:8000`
