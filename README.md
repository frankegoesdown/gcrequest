# gcrequest

a simple service for formatting JSON from curl's answer

## instal

```
go get github.com/frankegoesdown/gcrequest
```

## usage

```
gcrequest curl --location --request GET 'http://localhost:8080/todos' 

or 

gcrequest --location --request GET 'http://localhost:8080/todos' 
```
