# Writing an Interpreter in Go

This repository contains my personal code as I follow along with the book "Writing an Interpreter in Go" (V1.7).

## Book Sections

- [x] Chapter 1: Lexing
- [ ] Chapter 2: Parsing
- [ ] Chapter 3: Evaluation
- [ ] Chapter 4: Extending the Interpreter
  
## Getting Started

To run the REPL:

```sh
go run main.go
```

## Lexer

he Lexer reads an input string and tokenizes it into a series of tokens. It provides a NextToken method to sequentially retrieve the tokens.

## REPL

The Start function in the REPL package starts the REPL. It reads lines of input, tokenizes them using the Lexer, and prints the tokens.

## Token

The Token type represents a token produced by the Lexer. It has a type and a literal value.

## Contributing

As this is a personal learning project, contributions will not be accepted.

## Acknowledgments

Thorsten Ball for writing the book "Writing an Interpreter in Go".
