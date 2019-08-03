# consul_grpc_demo
Using consul as grpc register and discovery demo

### run
* run consul

```bash
consul agent -dev
```
   

* server

```bash
cd server
go mod tidy
go run cmd/main.go
```

    
  
* client 

```bash
cd client
go mod tidy
go run cmd/main.go
```

    
