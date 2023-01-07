# proglang3

## Launch
```bash
go run main.go -n 5
```

## Send message (token)
```bash
curl -X POST -d '{"data":"asdf", "recv":4, "ttl":4}' localhost:3333
```