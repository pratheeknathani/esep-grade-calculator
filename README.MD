# ESEP Grade Calculator

This repository contains a small Go library for calculating a final letter grade from assignment, exam, and essay scores.

## Tech Stack

- Go 1.24+
- Standard library `testing` package for unit tests

## Project Layout

- `go.mod`: Go module definition and language version.
- `grade_calculator.go`: grade calculator implementation.
- `grade_calculator_test.go`: unit tests for the calculator.
- `README.MD`: project overview and run instructions.

## Setup

From the repository root:

```bash
cd grade-calculator
```

## Run Tests

```bash
go test ./...
```

## Run Tests with Coverage

```bash
go test -coverprofile=coverage.out ./...
go tool cover -func=coverage.out
```

## Notes

- The calculator currently computes a weighted final letter grade from assignments, exams, and essays.
- Passing requires a `C` or better.