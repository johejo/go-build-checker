# go-build-checker

Building OSS written in Go using the Go master branch that often be called "tip" or "gotip".
This is to find compiler (or linker) bugs early and provide fast feedback.
Some projects may break for reasons unrelated to the compiler.

It's recommended to minimize repro code as much as possible before filing an issue, but this isn't always possible.

## GitHub Actions Workflow

[build](./.github/workflows/build.yml)

## Found issues

- https://github.com/golang/go/issues/44335
- https://github.com/golang/go/issues/44344
- https://github.com/golang/go/issues/44487
- https://github.com/golang/go/issues/44732
- https://github.com/golang/go/issues/45503
- https://github.com/golang/go/issues/45743
- https://github.com/golang/go/issues/47712
- https://github.com/golang/go/issues/48632
- https://github.com/golang/go/issues/49094
- https://github.com/golang/go/issues/49611
- https://github.com/golang/go/issues/53305
- https://github.com/golang/go/issues/54535
- https://github.com/golang/go/issues/54537
- https://github.com/golang/go/issues/60460
- https://github.com/golang/go/issues/62156
- https://github.com/golang/go/issues/63433
- https://github.com/golang/go/issues/73947

## License

MIT
