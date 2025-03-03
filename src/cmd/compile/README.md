# Go with While Loop Support

This is a custom fork of the Go programming language with added support for the `while` loop.

## Introduction

Go does not natively support `while` loops, relying instead on `for` loops to achieve similar functionality. This project extends Go by introducing a `while` loop syntax, making it easier for developers coming from other languages.

## Features

- Adds `while` loop syntax to Go.
- Maintains compatibility with existing Go features.
- Ensures seamless integration with Go's syntax and structure.

## Example Usage

```go
package main

import "fmt"

func main() {
  i := 0
  while i <= 10 {
    fmt.Println("Number: ", i)
    i++
  }
}
```

## Installation and Use

To build this version of Go, run:

```
/usr/bin/env bash $(pwd)/src/make.bash
```

Once built, you can run a sample code using:

```
bin/go run examples/while.go
```

## License

This project follows the original Go license (BSD-style).

