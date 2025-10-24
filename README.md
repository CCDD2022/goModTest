# GoModTest

just say hello

## Install

import code

```bash
go get github.com/CCDD2022/GoModTest@latest
```

install cmd

```bash
go install github.com/CCDD2022/GoModTest/cmd/hello@latest
```

## Example

Here's a simple example as follows:

```go
package main

import (
  "fmt"
  "github.com/CCDD2022/GoModTest"
)

func main() {
  result := hello.Hello("jack")
  fmt.Println(result)
}
```