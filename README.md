# args — Official Wyn Package

CLI argument parser. Pure Wyn.

## Install

```bash
wyn pkg install github.com/wynlang/args
```

## Usage

```wyn
var args = System.args()
var verbose = parse_flag(args, "--verbose")
var port = parse_value(args, "--port")
```
