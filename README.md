# rest-to-go
A REST API written in golang with swagger documentation included.

## Usefull commands
- `go run .` - run the application
- `go build .` - build the application (creates an executable)
- `go get .` - get all dependencies
- `go mod init rest-to-go-api` - create a new module
- `curl http://localhost:8080/albums` - get all albums
- `go install github.com/swaggo/swag/cmd/swag@latest` - install swag (for swagger documentation)
  - `export PATH=$(go env GOPATH)/bin:$PATH` - add go bin to path (for swag if not working)
- `go get -u github.com/swaggo/gin-swagger` - install gin-swagger
- `go get -u github.com/swaggo/files` - install files (for swagger)
- `swag init` - generate swagger documentation (run this in the root of the project each time to update the documentation)