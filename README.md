## GO-MOVIES-CRUD

*crud api with golang*

***attention*, external libs in project:**

    github.com/gorilla/mux

**in your terminal, run:**

    go run main.go

**struct:**

    {
        "id": "1",
        "isbn": "438227",
        "title": "Movie One",
        "director": {
            "firstname": "John",
            "lastname": "Doe"
        }
    }

**in your postman (or insomnia wtv), access the paths:** 

    GET (ALL) - http://localhost:8080/movies
    GET (BY ID) - http://localhost:8080/movies/{id}
    POST (CREATE) - http://localhost:8080/movies
    PUT (UPDATE) - http://localhost:8080/movies/{id}
    DELETE (DELETE) - http://localhost:8080/movies{id}