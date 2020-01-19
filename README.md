## Hash

```go
package main

import (
    "fmt"

    "github.com/golang-common-packages/template/common/util/hash"
)

func main() {
    client := &hash.Client{}

    fmt.Println(client.FNV32("Backend Golang"))
    fmt.Println(client.FNV32a("Backend Golang"))
    fmt.Println(client.FNV64("Backend Golang"))
    fmt.Println(client.FNV64a("Backend Golang"))
    fmt.Println(client.MD5("Backend Golang"))
    fmt.Println(client.SHA1("Backend Golang"))
    fmt.Println(client.SHA256("Backend Golang"))
    fmt.Println(client.SHA512("Backend Golang"))
}
```