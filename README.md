<div align="center">

# GO & Gin Minimal REST API

</div>

```go
package main

import (
    "net/http"

    "github.com/gin-gonic/gin"
)
```

#### get dependencies for code in the current directory.
```bash
$ go get .
go get: added github.com/gin-gonic/gin v1.7.2
```
Go resolved and downloaded this dependency to satisfy the import declaration you added in the previous step.

#### run code in the current directory
```
$ go run .
```

```bash
$ curl http://localhost:8080/albums
```
The command should display the data you seeded the service with.
```
[
        {
                "id": "1",
                "title": "Blue Train",
                "artist": "John Coltrane",
                "price": 56.99
        },
        {
                "id": "2",
                "title": "Jeru",
                "artist": "Gerry Mulligan",
                "price": 17.99
        },
        {
                "id": "3",
                "title": "Sarah Vaughan and Clifford Brown",
                "artist": "Sarah Vaughan",
                "price": 39.99
        }
]
```
