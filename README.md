# gotest

[![CircleCI](https://circleci.com/gh/rakyll/gotest.svg?style=svg)](https://circleci.com/gh/rakyll/gotest)

Like `go test` but with colors.

## Installation

Use the pre-built binary for Linux 64-bit:

```
$ curl http://storage.googleapis.com/jbd-releases/gotest_linux > gotest && chmod +x gotest
```

Alternatively:

```
$ go get -u github.com/rakyll/gotest
```

# Usage

Accepts all the arguments and flags `go test` works with.

Example:

```
$ gotest -v github.com/rakyll/hey
```
![go test output](https://i.imgur.com/udjWuZx.gif)

gotest comes with many colors! Configure the color of the output by setting the following env variable:

```
$ GOTEST_PALETTE="magenta,white"
```

The output will have magenta for failed cases, white for success.
Available colors: black, hiblack, red, hired, green, higreen, yellow, hiyellow, blue, hiblue, magenta, himagenta, cyan, hicyan, white, hiwhite.
