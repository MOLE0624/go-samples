# go-samples

## Env
Install Go: [Download Go](https://go.dev/dl/)

Verify installation:

``` bash
go version
```

## Usage

### New project

``` bash
go mod init <project name>
```

### Execution

option 1: Run a Go File

``` bash
go run <file-name>
```

option 2: Build and Execute a Go File

``` bash
go build <file-name>

./<binary-name>
```

## Cross compile

GOOS=\<OS\> GOARCH=\<Arch\> go build -o \<Output file name\> \<Go file name\>

``` bash
GOOS=linux GOARCH=amd64 go build -o hello hello.go
```

## Samples

### 1. hello

Run directly:

``` bash
go run hello.go
```

Build and run:
``` bash
go build hello.go

./hello
```
