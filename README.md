# healthyBot

- run
```
GOOS=linux GOARCH=amd64 go build -tags lambda.norpc -o bootstrap main.go
```

- upload to AWS lambda layer
  - upload by .zip file
  - choose amd64
  - choose Amazon Linux 2
