---
theme: ./path/to/theme.json
author: 코딩문
date: "Go 프로그래밍"
paging: Slide %d / %d
---

# Hello World

- Go 설치
- Hello World 프로그램

---

# Go 설치 방법

1. `https://go.dev/doc/install`
   <br/>
2. `brew install go` (OSX)

---

# Go 버젼 확인

```bash

$ go version

"go version go1.21.5 darwin/arm64"

```
---

# Hello World 프로그램


```go
// hello_world.go

package main 

import "fmt"

func main() {
    fmt.Println("Hello World")
}


```

---

# 프로그램 실행


`Build` Command
```bash
$ go build hello_world.go

$ ./hello_world

"Hello World"

```
`Run` Command

```bash
$ go run hello_world.go

"Hello World"

```

> 디렉토리안의 파일을 선택할때 `.` 사용 가능 

---

# Go Playground


`https://go.dev/play`


