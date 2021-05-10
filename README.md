
# Iniciar proyecto
```
    git init .
    gh auth login 
        GitHub.com/HTTPS/Yes/Login with a web browser
    gh repo create yogparra/go-rest-api
        Public/Yes
    go mod init github.com/yogparra/go-rest-api
    --go mod tidy
```

# Ruta
```
    go run cmd/server/main.go
```    

# Go
```
    go version
    go version go1.16.3 windows/amd64
```

# Go test Ci git action
```
go test -v -cover ./../..
```