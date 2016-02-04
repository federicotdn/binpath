# binpath
Go library to check if a file path is binary, based on its extension.  Based on the JavaScript [`is-binary-path`](https://github.com/sindresorhus/is-binary-path) module.

## Installation
```bash
$ go get github.com/federicotdn/binpath
```

## Usage
```go
import "github.com/federicotdn/binpath"

binpath.IsBinaryPath("foo/bar.jpg")
//=> true

binpath.IsBinaryPath("foo/bar.txt")
//=> false
```

## License
MIT License.
