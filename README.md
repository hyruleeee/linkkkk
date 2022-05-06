# Linkkkk

Go!

## Compile and Install the Application

### Compile

`go build`

`./hello`

### Install

```zsh
export GO_INSTALL_DIR=$(dirname $(go list -f '{{.Target}}'))
export PATH=$PATH:$GO_INSTALL_DIR
go env -w GOBIN=$GO_INSTALL_DIR
go install
hello
```
