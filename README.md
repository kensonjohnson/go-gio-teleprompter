# Teleprompter with Go and Gio

This is result of following [this tutorial](https://jonegil.github.io/gui-with-gio/teleprompter/).
Few diviations were made from the original code.

## Prerequisites

[Go](https://go.dev/) is the only requirment.

Optionally, I use [Just](https://just.systems/) as my command runner.

## Getting Started

1. If haven't already, clone the repo:

```sh
git clone git@github.com:kensonjohnson/go-gio-teleprompter.git
cd go-gio-teleprompter
```

2. Fetch needed dependencies: `just tidy` or `go mod tidy`

3. Run the app: `just run` or `go run .`

