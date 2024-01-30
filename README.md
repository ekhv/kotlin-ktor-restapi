# Tutorial: Tutorial: Simple Kotlin REST API with Ktor, Exposed and Kodein

This repository contains the code for my tutorial: [Tutorial: Simple Kotlin REST API with Ktor, Exposed and Kodein](https://stefangaller.at/app-development/backend/ktor-rest-api-exposed/)

all books
```shell
curl -s http://localhost:8080/api/v1/books
```

add book
```shell
curl -s --request POST http://localhost:8080/api/v1/book \
--header 'Content-Type: application/json' \
--data '{"title": "my new book","author": "new author"}'
```

delete book
```shell
curl -s --request DELETE http://localhost:8080/api/v1/book/1
```