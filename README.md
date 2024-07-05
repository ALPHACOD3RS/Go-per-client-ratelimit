# Go-per-client-ratelimit

This project implements a rate limiting mechanism for Go clients.

## Installation

To install the project, you can use the following command:

- cd to the project
- go run main.go

## In another terminal

# To call once

- curl -i http://localhost:8000/test

# To call Multiple

- for i in {1..8}; do curl http://localhost:8000/test; done
