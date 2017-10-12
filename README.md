# sparta-sandbox

Sandbox for sparta with http://gosparta.io/docs/intro_example/step1/

## Requirements

* AWS Credentials
* `$S3_BUCKET`

## Deploy

```
$ go run main.go --level info describe --out ./graph.html --s3Bucket $S3_BUCKET
$ go run main.go provision --s3Bucket $S3_BUCKET
```

## Delete stack

```
$ go run main.go delete
```
