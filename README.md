# gcrequest

a simple service for formatting JSON from curl's answer

## instal

```
go get github.com/frankegoesdown/gcrequest
cd ~/go/github.com/frankegoesdown/gcrequest
go build -o gcr
sudo mv gcr /usr/local/bin/gcr
```

## usage

```
gcr curl --location --request GET 'http://localhost:8080/todos' 

or 

gcr --location --request GET 'http://localhost:8080/todos' 
```
