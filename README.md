# Golang Main Function Generator (gRPC)

Use this protoc plugin to generate a main.go for a grpc service.

```sh
# Install
go get github.com/nstogner/protoc-gen-grpc-go-main

# This assumes that $GOPATH/bin is a part of $PATH
protoc --grpc-go-main_out=./grpcd example.proto
```
