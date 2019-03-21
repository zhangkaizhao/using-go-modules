# Code snippets of using go modules article

via [Using Go Modules](https://blog.golang.org/using-go-modules)

* [a](a): creating a new module
* [b](b): adding a dependency
* [b1](b1): upgrading dependencies
* [b2](b2): test failure on incompatible dependencies
* [b3](b3): use explicit version to resolve incompatible
* [c](c): adding a dependency on a new major version
* [c1](c1): upgrading a dependency to a new major version
* [d](d): removing unused dependencies

> Module functionality is now available in all supported Go versions (that is, in **Go 1.11** and **Go 1.12**).
>
> This post introduced these workflows using Go modules:
>
> * `go mod init` creates a new module, initializing the `go.mod` file that describes it.
> * `go build`, `go test`, and other package-building commands add new dependencies to `go.mod` as needed.
> * `go list -m all` prints the current module’s dependencies.
> * `go get` changes the required version of a dependency (or adds a new dependency).
> * `go mod tidy` removes unused dependencies.
