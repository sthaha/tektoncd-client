# Development

This doc explains how to setup a development environment so you can get started
[contributing](https://github.com/tektoncd/pipeline/blob/master/CONTRIBUTING.md) to `Tekton Client`.

## Building Tekton Client

**Dependencies:**

[go mod](https://github.com/golang/go/wiki/Modules#quick-start) is used and required for dependencies.

**Building:**

```sh
$ go build ./cmd/...
```

It builds `tkn` binary in your current directory. You can start playing with it.

**Notes:**

- For building, Go `1.12` is required
- If you are building in your `$GOPATH` folder, you need to specify `GO111MODULE` for building it

```sh
# if you are building in your $GOPATH
GO111MODULE=on go build ./cmd/...
```

You can now try updating code for client and test out the changes by building the `tkn` binary.
