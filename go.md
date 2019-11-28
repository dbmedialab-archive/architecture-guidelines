# Go

**Repository**
- github for centralized git repo

**Packages**

>  package's name is a one word elevator pitch for what it provides--not what it contains.

**Diskusjon**

- Dependencies
  - Vendoring (https://github.com/golang/dep)
- Router
  - Gorilla Mux
- Konfigurasjon
  - [Godotenv](https://github.com/joho/godotenv)
- Metrics/Monitorering
  - Prometheus go client
- Logging
  - Stderr: produksjonslogg, `log.SetFlags(log.Llongfile)`
  - Stdout: debuglogg: `fmt`
- Databasedriver
  - https://github.com/go-sql-driver/mysql
  - https://github.com/lib/pq
- ORM?
  - Nei?
  - Rene SQL statements med sqlx
- Templating?
  - Innebygd (html/template, text/template)
- GRPC (tenke på senere)
  - Med https://github.com/grpc-ecosystem/grpc-gateway
- Rammeverk?
  - Nei
- Testing
  - Innebygd: https://godoc.org/testing

**Prosjektstruktur**
- `/github.com/dbmedialab/project/`
  - `/cmd/[service]/` (Binary files `package main`)
  - `/proto/` (GRPC Protobuf files)
  - `/service/` (generated GRPC service files)
  - `/client/` (generated GRPC client files)
  - `/` Package files

Only create new sub packages when there are at least 3 types that fits into the package scope.

Links:

https://github.com/golang/go/wiki/CodeReviewComments

http://golang.org/doc/effective_go.html
