# Go-lang Import CSV into SQLite
This go-lang code is used to import data from CSV file into the SQLite database.

# Manual Steps: 
``` shell
apt install golang
```

``` shell
go version
```
# go version go1.20.3

# config
``` shell
 set GOOS=linux
 set GOARCH=amd64
 set CGO_ENABLED=0
```

# install sqlite 
``` shell
go get github.com/modernc.org/sqlite
```

# executing go program
```shell
go run main.go
```

This go-lang code is used to import one by one record from CSV file into the SQLite database.

The first record took ***1.5 sec*** to import a single row.
It looks too long compared to Python and PHP. This slow performance is because of go-sqlite3 cgo package issue- [Slow performance on insert in ](https://github.com/mattn/go-sqlite3/issues/1145) 
