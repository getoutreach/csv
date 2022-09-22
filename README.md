# csv
[![go.dev reference](https://img.shields.io/badge/go.dev-reference-007d9c?logo=go&logoColor=white)](https://engdocs.outreach.cloud/github.com/getoutreach/csv)
[![CircleCI](https://circleci.com/gh/getoutreach/csv.svg?style=shield&circle-token=f28170e343fd8526a5d3e6cd427ebc93bbeb2803)](https://circleci.com/gh/getoutreach/csv)
[![Generated via Bootstrap](https://img.shields.io/badge/Outreach-Bootstrap-%235951ff)](https://github.com/getoutreach/bootstrap)
[![Coverage Status](https://coveralls.io/repos/github/getoutreach/csv/badge.svg?branch=main)](https://coveralls.io/github//getoutreach/csv?branch=main)
<!-- <<Stencil::Block(extraBadges)>> -->

<!-- <</Stencil::Block>> -->

CSV library forked from encoding/csv without CRLF handling

## Contributing

Please read the [CONTRIBUTING.md](CONTRIBUTING.md) document for guidelines on developing and contributing changes.

## High-level Overview

<!-- <<Stencil::Block(overview)>> -->

Standard CSV reader from [enconding/csv](https://pkg.go.dev/encoding/csv) package does [modify the data](https://github.com/golang/go/issues/22746).
It converts CRLF to just LF.
This package is fork of the package with CRLF handling removed.

Usage is the same as for the [original package](https://pkg.go.dev/encoding/csv).

<!-- <</Stencil::Block>> -->
