# checker

[![Build Status](https://github.com/pipebuild/checker/workflows/ci/badge.svg?branch=main&event=push)](https://github.com/pipebuild/checker/actions?query=workflow%3Aci)
[![codecov](https://codecov.io/gh/pipebuild/checker/branch/main/graph/badge.svg?token=7PMQALLZLY)](https://codecov.io/gh/pipebuild/checker)
[![Go Report Card](https://goreportcard.com/badge/github.com/pipebuild/checker)](https://goreportcard.com/report/github.com/pipebuild/checker)
[![License](https://img.shields.io/github/license/pipebuild/checker.svg)](https://github.com/pipebuild/checker/blob/main/LICENSE)
[![Tag](https://img.shields.io/github/tag/pipebuild/checker.svg)](https://github.com/pipebuild/checker/tags)



## Introduction

*checker* is the checker of [pipebuild](https://github.com/pipebuild) written in Go.



## Prerequisites

- Go >= 1.18.0



## Run

```bash
version=latest make build
./bin/checker --config-file="$PWD"/test/config/config.yml
```



## Docker

```bash
version=latest make docker
docker run -v "$PWD"/test:/tmp ghcr.io/pipebuild/checker:latest --config-file=/tmp/config/config.yml
```



## Usage

```
usage: checker --config-file=CONFIG-FILE [<flags>]

pipebuild checker

Flags:
  --[no-]help                Show context-sensitive help (also try --help-long
                             and --help-man).
  --[no-]version             Show application version.
  --config-file=CONFIG-FILE  Config file (.yml)
```



## Settings

*checker* parameters can be set in the directory [config](https://github.com/pipebuild/checker/blob/main/config).

An example of configuration in [config.yml](https://github.com/pipebuild/checker/blob/main/config/config.yml):

```yaml
TBD
```



## License

Project License can be found [here](LICENSE).



## Reference
