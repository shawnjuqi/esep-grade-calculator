# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade-calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade-calculator/
go test -coverprofile=coverage.txt ./...
```

This repository contains four files:
- `go.mod` -> instantiates the folder grade_calculator as module and defines the runtime environment
- `grade_calculator.go` -> contains the grade calculator business logic in its class, functions, variables, and types
- `grade_calculator_test.go` -> contains 3 unit tests for grade calculating using the Go testing library
- `README.MD` -> contain information about what is needed to and how to run the code in this repository
