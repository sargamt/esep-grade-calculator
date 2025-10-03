# ESEP Grade Calculator

This library is a simple utility to calculate your final letter grade.

Runtime requirements:
Golang 1.24+ [Download here](https://go.dev/dl/)

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Code coverage shows how much of the code in your module has been "covered" or checked by the tests ran.

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```

To see what parts of your code have been "covered" in your tests, run:

```
cd grade_calculator/
go tool cover -html=coverage.txt
```