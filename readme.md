# REATful API with GO
#### From Golang tutorial website


In this code, we use the Gin Web Framework along with Golang to create a RESTful API. For this example, we used in memory storage rather than creating a database. The main idea was to supply the user with the album(s) data when they react out to API endpoint /album at port 8080.

To run the code, open terminal and run

```
$ go get .
```

To download all the dependency required for the code to run, and then 

```
$ go run .
```

To run the code

To get the data on the client side, send a GET request with the following command

```
$ curl http://localhost:8080/albums
```

## Happy Coding ^_^