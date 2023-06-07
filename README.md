# protoc-gen-go-defaults

This is a fork of [protoc-gen-defaults](https://github.com/linka-cloud/protoc-gen-defaults).

## Usage

```
# buf.gen.yaml
version: v1

managed:
  enabled: true

plugins:
  - name: gapi-lint
    out: internal/proto
```
