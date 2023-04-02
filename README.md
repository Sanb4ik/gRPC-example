# gRPC server-client application
This mono repository contains a sample of micro-services architecture built on top of gRPC protocol and JavaScript node.js applications


## Getting started

Install `protoc` for generating definitions based on `.proto` files

```shell
sudo snap install protobuf --classic
protoc --version  # Ensure compiler version is 3+
```

Prepare environment
```shell
npm install
```

Start
```
    node "1. download prices"
    node "2. generate protobuf runtime"
    node "3. run protobuf transformation": "node protoc.js",
    node "4. start grpc server": "node grpc-server.js",
    node "5. start grpc client": "node grpc-client.js"
```
