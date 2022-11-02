add to ~/.bash_profile
```
export GO111MODULE=on
export GOPROXY=https://goproxy.cn
```

```shell script
go mod init example.com/hello
go test
go get golang.org/x/text
go list -m all
go list -m -versions rsc.io/sampler
go get rsc.io/sampler@v1.3.1
go mod tidy
```
