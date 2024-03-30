---

# FizzBuzz in Go

This is an implementation of the classic programming problem "FizzBuzz" in the Go programming language.

## Problem Statement

Write a program that prints the numbers from 1 to 100. But for multiples of three print "Fizz" instead of the number and for the multiples of five print "Buzz". For numbers which are multiples of both three and five print "FizzBuzz".

## Solution

This program uses a `for` loop to iterate from 1 to 100. For each number, it uses a `switch` statement to check if the number is a multiple of 3 and 5, only 3, only 5, or none of them, and prints the corresponding result.

## How to Run

You can run this program by using the `go run` command followed by the filename:

```bash
go run fizzbuzz.go
```

This will print the numbers from 1 to 100, but for multiples of three it will print "Fizz" instead of the number and for multiples of five it will print "Buzz". For numbers which are multiples of both three and five it will print "FizzBuzz".

---
