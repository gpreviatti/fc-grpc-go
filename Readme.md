# FullCycle GRPC Go

Simple application usign Golang and Grpc

## Tips

[Quick start Grpc with Go](https://grpc.io/docs/languages/go/quickstart/)

[Proto C installation](https://grpc.io/docs/protoc-installation/)

[Grpc Client](https://github.com/ktr0731/evans)

Generating entities and services with protoc

`protoc --go_out=. --go-grpc_out=. proto/course_category.proto`

If you had this output when you try to compile the files install the package below.

```
protoc-gen-go-grpc: program not found or is not executable
--go-grpc_out: protoc-gen-go-grpc: Plugin failed with status code 1.
```

`go install google.golang.org/grpc/cmd/protoc-gen-go-grpc@latest`

Enter inside evans client 

`evans -r repl`
