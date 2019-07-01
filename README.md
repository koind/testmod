# testmod

# How use?
1. go mod init [name]
2. go build (In go.mod added request package and version) "require github.com/koind/testmod v1.0.0"
3. go get -u (Get new version data and files) "require github.com/koind/testmod v1.0.1"
4. go get github.com/koind/testmod@v1.0.0 (Roll back old version)
5. go mod tidy - clear on old request in go.mod and go.sum
6. go mod vendor - download all dependencies in local PC
7. go build --mod vendor - When building data get in local vendor
