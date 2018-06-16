# go-flv

[![CircleCI](https://circleci.com/gh/yutopp/go-flv.svg?style=svg)](https://circleci.com/gh/yutopp/go-flv)
[![Coverage Status](https://coveralls.io/repos/github/yutopp/go-flv/badge.svg)](https://coveralls.io/github/yutopp/go-flv)
[![Go Report Card](https://goreportcard.com/badge/github.com/yutopp/go-flv)](https://goreportcard.com/report/github.com/yutopp/go-flv)

FLV decoder/encoder library written in Go.

- [ ] decoder
  - [x] header
  - [x] body
  - [ ] tags
    - [x] flv
    - [x] audio
    - [x] video
    - [ ] data
    - [ ] onMetaData
- [ ] encoder
  - [x] header
  - [x] body
  - [ ] tags
    - [x] flv
    - [x] audio
    - [x] video
    - [ ] data
    - [ ] onMetaData
  
## Installation

```
go get github.com/yutopp/go-flv
```

## Examples

- [yutopp/go-flv-examples](https://github.com/yutopp/go-flv-examples)

## License

[Boost Software License - Version 1.0](./LICENSE_1_0.txt)

## References

- [spec](https://wwwimages2.adobe.com/content/dam/acom/en/devnet/flv/video_file_format_spec_v10.pdf)
  - The FLV File Format
