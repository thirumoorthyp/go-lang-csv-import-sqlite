# go-lang-csv-import-sqlite
This go lang code is used to import data from CSV file into sqlite database.

apt install golang

go version
# go version go1.20.3

# config
 $env:GOOS = "linux"
 set GOOS=linux
 set GOARCH=amd64
 set CGO_ENABLED=0

# install splite3
go install splite3 

# executing go program
go run insert csv file data.go
