# favicon-generator

Command-line to generate favicons from a image.

## Installation

Install [libvips](https://github.com/libvips/libvips):

```shell
$ apt install libvips-dev
```

You need `go` installed and `GOBIN` in your `PATH`. Once that is done, run the
command:

```shell
$ go install github.com/cgroschupp/favicon-generator@latest
```

## Usage

```
NAME:
   favicon-generator - Command-line to generate favicons from a image.

USAGE:
   favicon-generator [global options] command [command options]

COMMANDS:
   help, h  Shows a list of commands or help for one command

GLOBAL OPTIONS:
   --input value, -i value                            Input image
   --output value, -o value                           Folder to output the favicons (default: "favicons")
   --size value, -s value [ --size value, -s value ]  (default: 32, 57, 76, 96, 120, 128, 144, 152, 180, 195, 196, 228, 270, 558)
```
