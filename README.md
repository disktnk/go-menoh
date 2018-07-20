at 7/4/2018 13:00 renamed the repository name to **go-menoh** from menoh-go, following [recommended naming rule](https://github.com/golang/go/wiki/PackagePublishing)

# Menoh Go

[![Build Status](https://travis-ci.org/pfnet-research/go-menoh.svg?branch=master)](https://travis-ci.org/pfnet-research/go-menoh)

Golang binding for [Menoh](https://github.com/pfnet-research/menoh)

## Requirements

- Go 1.10+
- [Menoh](https://github.com/pfnet-research/menoh) 1.0.1+

## Install

After install Menoh, then

```bash
$ go get -u github.com/pfnet-research/go-menoh
```

### Linux/Mac

Add a path to library to `LD_LIBRARY_PATH` environment variable. Menoh libraries are installed to `/usr/local/lib` on default.

```bash
$ export LD_LIBRARY_PATH=/usr/local/lib:$LD_LIBRARY_PATH
```

### Windows

Add a path to DLLs distributed by Menoh to local Path environment.

```
\path\to\menoh\bin
  |- libiomp5md.dll
  |- menoh.dll
  |- mkldnn.dll
  |- mklml.dll
```

```cmd
set PATH=\path\to\menoh\bin;%PATH%
```


## Usage

See [example/vgg16/tutorial](example/vgg16/README.md)

## License

MIT License (see [LICENSE](/LICENSE) file).
