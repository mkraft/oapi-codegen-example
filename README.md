```shell
go generate ./...

go run petstore.go

curl 'http://localhost:8080/pets' \
  -H 'Content-Type: application/json' \
  -d '{"name": "max"}'

curl 'http://localhost:8080/pets'
```