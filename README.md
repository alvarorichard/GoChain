



# GoChain 

This project is an implementation of a basic blockchain in Go. It demonstrates the creation of blocks, validation of blocks, and the replacement of the blockchain. It also includes a simple HTTP server that allows adding blocks to the blockchain via POST requests and retrieving the blockchain via GET requests.


## Prerequisites
 To run this project, you need to have the following installed:

* Go programming language (version 1.16 or later)
* Gorilla Mux package
* Go-Spew
* GodoTenv

## Getting Started

```shell
git clone https://github.com/alvarorichard/GoChain
```
Enter to the project directory
```shell
cd GoChain
```

Install the necessary dependencies

```go
go get github.com/davecgh/go-spew/spew

go get github.com/gorilla/mux

go get github.com/joho/godotenv
```

## Run the project.

```go

go run main.go
```
The HTTP server will start running and listen for incoming requests on the specified address and port.

API Endpoints
GET /

Retrieves the entire blockchain

POST /

Adds a new block to the blockchain.
Request Body

The request body should be a JSON object with the BPM field representing the beats per minute.

# Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create an issue or submit a pull request.

